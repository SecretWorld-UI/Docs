# [ class ] com.GameInterface.Game.Shortcut

# [ group ] Variables

# [ variable ] m_ShortcutList

Associavite array of all the shortcut the player has

---

# [ group ] Functions

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

# [ function ] RemoveAugment

Try to remove an augment SignalShortcutRemoved will be triggered if the remove was legal.

## Parameters

<pre>
<em>itemPos</em> | :Number   The augment to remove.
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

# [ function ] AddAugment

Add an augment to a slot. SignalShortcutAdded will be called on success.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position on the bar.
<em>spellId</em> | :Number   The spell to auto add.  
</pre>

---

# [ function ] AddItem

Add an item to a slot. SignalShortcutAdded will be called on success.

## Parameters

<pre>
<em>shortcutPos</em> | :Number   The position on the bar.                 
<em>inventoryId</em> | :Number   From which inventory its added.          
<em>itemPos</em>     | :Number   The itemposition in the inventory to add.
</pre>

---

# [ function ] GetNumPocketSlots

Gets the number of usable pocket slots

---

# [ function ] GetMaxPocketSlots

Gets the max number of pocket slots

---

# [ function ] IsSpellEquipped

# [ group ] Variables

# [ variable ] SignalShortcutAdded

Signal sent when a shortcut has been added. This also happens when you teleport to a new pf. Note that you might get an SignalShortcutEnabled right afterward if the shortcut is disabled. And SignalCooldownTime if it's in cooldown.

## Parameters

<pre>
<em>itemPos</em>   | :Number   The position the item was added to. This is used for refering to this item.
<em>name</em>      | :String      The name of the item in LDB format.                                     
<em>icon</em>      | :String      The icon resource information.                                          
<em>itemClass</em> | :Number The type of shortcut. See Enums.StatItemClass                                
</pre>

---

# [ variable ] SignalShortcutRemoved

Signal sent when a shortcut has been removed. This will not be sent if the shortcut changes position, moved.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ variable ] SignalShortcutMoved

Signal sent when a shortcut has been move to some other spot. No add/remove signal will be triggered.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position the item was move from.
<em>toPos</em>   | :Number     The position the item was move to.
</pre>

---

# [ variable ] SignalHotkeyChanged

Signal sent when a hotkey is changed

## Parameters

<pre>
<em>hotkeyId</em> | :Number  ID of the changed hotkey
</pre>

---

# [ variable ] SignalShortcutStatChanged

Signal sent when a shortcut changed one of it's stats. Probably most usefull for stacksize changes.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.                   
<em>stat</em>    | :Number      The stat that changed. See Enums/Stats.as
<em>value</em>   | :Number     The new value for the stat.               
</pre>

---

# [ variable ] SignalShortcutEnabled

Signal sent when a shortcut is enabled/disabled. Will also be send when you enter a new playfield.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Boolean    Enabled/Disabled       
</pre>

---

# [ variable ] SignalShortcutRangeEnabled

Signal sent when a shortcut is enabled/disabled via range.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Boolean   Enabled/Disabled        
</pre>

---

# [ variable ] SignalShortcutUsed

Signal sent when a shortcut is used

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
</pre>

---

# [ variable ] SignalShortcutAddedToQueue

Signal sent when a shortcut is added to the queue

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
</pre>

---

# [ variable ] SignalShortcutRemovedFromQueue

Signal sent when a shortcut is removed from the queue

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
</pre>

---

# [ variable ] SignalCooldownTime

Signal sent when a shortcut enters cooldown. Will also be send when you enter a new playfield.

## Parameters

<pre>
<em>itemPos</em>      | :Number   The position of the item.                  
<em>seconds</em>      | :Number   The cooldown time in seconds left.         
<em>cooddownType</em> | :Number  The cooldown type from Enums.TemplateLock...
</pre>

---

# [ variable ] SignalShortcutsRefresh

Signal sent when the shortcut list has been loaded or when something else has forced it to be refreshed. So this will be called on login at least. Normal response to this call is RefreshShortcuts( fromPos, count )

---

# [ variable ] SignalSwapShortcut

Signal sent when a shortcut enters or exits max momentum (all resources filled up or not). / @param itemPos:Number   The position of the item. public static var SignalShortcutMaxMomentumEnabled:Signal; // -> SlotSignalShortcutMaxMomentumEnabled( itemPos:Number, enabled:Boolean )

---

# [ variable ] SignalSwapBar

# [ variable ] SignalRestoreSwapBar

# [ variable ] SignalNumPocketSlotsChanged

