# [ class ] com.GameInterface.UtilsBase

# [ group ] Functions

# [ function ] PrintChatText

# [ function ] ParseHTMLColor

# [ function ] ParseHTMLFont

# [ function ] PlaySound

# [ function ] PlayFeedbackSound

# [ function ] PlayFeedbackSoundEnum

# [ function ] GetGameTweak

Get a tweakvalue. This should preferable only be done once at startup, per value you need. Instead of every time you need it. In the case of changing the tweak, the .swf file should be reloaded to get this value again.

## Parameters

<pre>
<em>name</em>  | [in]  The name of the tweakvalue.                
<em>param</em> |          [out] The value. Returns 0 if not found.
</pre>

---

# [ function ] GetGameTime

Get the scalable (affected by the /time chat command) timer used by most systems in the game. Granularity is milliseconds or better.

---

# [ function ] GetNormalTime

# [ function ] GetTimeOfDay

# [ function ] GetServerSyncedTime

Get GMT time syncronized with the server. Granularity is seconds.

---

# [ function ] GetServerUpTime

# [ function ] StartTrade

# [ function ] AcceptTrade

# [ function ] NoLongerAcceptTrade

# [ function ] AbortTrade

# [ function ] AttenuateGameSounds

# [ function ] SetTradeCash

# [ group ] Variables

# [ variable ] SignalSplashScreenActivated

Signal sent when the splashscreen is activated or deactivated.

## Parameters

<pre>
<em>activated</em> | :Boolean    True if splash was shown, else false.
</pre>

---

# [ variable ] SignalLoginPrefsLoaded

Signal sent when login prefs has been loaded. This happens right after you have logged in.

## Parameters

<pre>
<em>reloaded</em> | :Boolean    True if it was a reload.
</pre>

---

# [ variable ] SignalLoginPrefsPostUnload

Signal sent when you've logged out.

---

# [ variable ] SignalCharacterPrefsLoaded

Signal sent when you chosen a character and it's prefs has been loaded.

## Parameters

<pre>
<em>reloaded</em> | :Boolean    True if it was a reload.
</pre>

---

# [ variable ] SignalCharacterPrefsPreUnload

Signal sent when the characters prefs are about to be unloaded.

---

# [ variable ] SignalCharacterPrefsPostUnload

Signal sent when the characters prefs has been unloaded.

---

# [ variable ] SignalObjectUnderMouseChanged

# [ variable ] SignalTradeStarted

# [ variable ] SignalTradeEnded

# [ variable ] SignalPartnerAccepted

# [ variable ] SignalPartnerNoLongerAccepted

# [ variable ] SignalClientCharAccepted

# [ variable ] SignalClientCharNoLongerAccepted

# [ variable ] SignalPartnerCashUpdated

