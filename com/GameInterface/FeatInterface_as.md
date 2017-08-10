# [ class ] com.GameInterface.FeatInterface

# [ group ] Variables

# [ variable ] m_FeatList

Associavite array of all the spells the player has. This object is supposed to be const, but that is not supported in actionscript. This list will be kept in sync by gamecode but you will have to call BuildFeatList when you show the feat gui. You will get signals when the state of the list changes.

---

# [ group ] Functions

# [ function ] TrainFeat

Train a feat. If it fail, message will pop on screen and false will be returned. SignalFeatTrained will be called on success.

## Parameters

<pre>
<em>featId</em> | [in]  The feat to train.                                                 
<em>param</em>  |         [out] True if all preliminary client checks was ok. False if not.
</pre>

---

# [ function ] RefundFeat

Refund a feat.

## Parameters

<pre>
<em>featId</em> | [in]  The feat to refund.
</pre>

---

# [ function ] BuildFeatList

Request gamecode to rebuild the featlist. This should be called when you open the feat gui. Should also be called if featpoints or level of the clientchar changes.

---

# [ group ] Variables

# [ variable ] SignalFeatTrained

Signal sent when a new feat was trained. The m_FeatList has been update.

## Parameters

<pre>
<em>featId</em> | :Number    The feat that was trained.
</pre>

---

# [ variable ] SignalFeatsUntrained

Signal sent if all feats were untrained. The m_FeatList has been cleared.

---

# [ variable ] SignalOpenTrainFeatGUI

Signal sent if gamecode wants us to show the feat gui.

---

# [ variable ] SignalCloseTrainFeatGUI

Signal sent if gamecode wants us to close the feat gui.

---

# [ variable ] SignalFeatListRebuilt

