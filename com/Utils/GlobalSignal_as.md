# [ class ] com.Utils.GlobalSignal

Signals sent from gamecode.

---

# [ group ] Variables

# [ variable ] SignalDamageNumberInfo

OnScreen damage numbers and related into.

## Parameters

<pre>
<em>statID</em>               | :Number                  The stat that was affected                               
<em>damage</em>               | :Number                  The amount to withdraw/add to that stat                  
<em>attackResultType</em>     | :Number        The attack result type (Enums.AttackResultType).                   
<em>attackType</em>           | :Number        The attack type (Enums.AttackType (Melee, ranged, Magic) ).        
<em>attackOffensiveLevel</em> | :Number    The offensive level of the attack (Enums.AttackOffensiveLevel)         
<em>attackDefensiveLevel</em> | :Number    The defensive level of the attack (Enums.AttackDefensiveLevel)         
<em>context</em>              | :Number                 Enums.InfoContext       - Yourself, your target or others.
<em>targetID</em>             | :ID32                  The targetid                                               
</pre>

---

# [ variable ] SignalDamageTextInfo

Show text flying over head.

## Parameters

<pre>
<em>text</em>     | :String                    The text to show                                       
<em>context</em>  | :Number                 Enums.InfoContext       - Yourself, your target or others.
<em>targetID</em> | :ID32                  The targetid                                               
</pre>

---

# [ variable ] SignalShowInspectWindow

Show inspect window

## Parameters

<pre>
<em>text</em> | :String                    Show Inspect window for a character
</pre>

---

# [ variable ] SignalFadeScreen

Fade screen in or out.

## Parameters

<pre>
<em>fadeIn</em> | :Boolean   True if screen should fade back in. False if the screen should fade to black.
<em>time</em>   | :Number      The time the fade should take in seconds.                                  
</pre>

---

# [ variable ] SignalLootBagOpened

Loot bag opened.

## Parameters

<pre>
<em>id</em> | :com.Utils:ID32 Loot bag ID.
</pre>

---

# [ variable ] SignalMissionReportSent

MissionReport Sent

---

# [ variable ] SignalMissionReportWindowClosed

Mission Report window has been closed

---

# [ variable ] SignalShowFriendlyMenu

# [ variable ] SignalClaimRowSelected

Claim Window row selection toggle between multiple instances

---

# [ variable ] SignalSetGUIEditMode

# [ variable ] SignalAbilityBarDrag

# [ variable ] SignalScryTimerLoaded

# [ variable ] SignalScryCounterLoaded

# [ variable ] SignalScryTimerCounterComboLoaded

# [ variable ] SignalInterfaceOptionsReset

# [ variable ] SignalShowPassivesBar

# [ variable ] SignalSendItemToUpgrade

# [ variable ] SignalSendItemToCrafting

# [ variable ] SignalSendItemToBank

# [ variable ] SignalSendItemToTradepost

# [ variable ] SignalSendItemToTrade

# [ variable ] SignalCrosshairTargetUpdated

