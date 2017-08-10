# [ class ] com.GameInterface.Game.ShortcutBase

# [ group ] Functions

# [ function ] GetShortcutData

Get information about the item equipped at itemPos in the shortcut interface.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position pf the item to query
</pre>

---

# [ function ] RefreshShortcuts

Forces the client to send add or remove signal for each of the slots in the range.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position to start the refersh from.
<em>count</em>   | :Number     Number of positions to refresh.      
</pre>

---

# [ function ] MoveShortcut

Try to move a shortcut to a new pos. If the move was allowed, SignalShortcutMoved will be triggered.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position to move from.
<em>toPos</em>   | :Number     The position to move to.
</pre>

---

# [ function ] RemoveFromShortcutBar

Try to remove a shortcut. SignalShortcutRemoved will be triggered if the remove was legal.

## Parameters

<pre>
<em>itemPos</em> | :Number   The shortcut to remove.
</pre>

---

# [ function ] UseShortcut

Try to use a shortcut. You will not know the outcome, but you might get a SignalCooldownTime.

## Parameters

<pre>
<em>itemPos</em> | :Number   The shortcut to use.
</pre>

---

# [ function ] AddSpell

Add a spell to a slot. SignalShortcutAdded will be called on success.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position on the bar.
<em>spellId</em> | :Number   The spell to auto add.  
</pre>

---

