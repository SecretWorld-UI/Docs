# [ class ] GUI.SkillHive.SkillhivePassiveAbilityBar

# [ group ] Variables

# [ variable ] m_NumAbilities

# [ variable ] m_PassiveAbilitySlots

# [ variable ] SignalToggleVisibility

# [ group ] Functions

# [ function ] SkillhivePassiveAbilityBar

# [ function ] onLoad

# [ function ] onUnload

# [ function ] CanAddPassive

# [ function ] SlotToggleVisibility

# [ function ] EquipPassive

# [ function ] UnEquipPassive

# [ function ] HighlightSlot

# [ function ] StopHighlightSlot

# [ function ] SlotPassiveAdded

Signal sent when a shortcut has been added. This also happens when you teleport to a new pf. Note that you might get an SignalShortcutEnabled right afterward if the shortcut is disabled. And SignalCooldownTime if it's in cooldown.

## Parameters

<pre>
<em>itemPos</em>   | :Number   The position the item was added to. This is used for refering to this item.
<em>name</em>      | :String      The name of the item in LDB format.                                     
<em>icon</em>      | :String      The icon resource information.                                          
<em>itemClass</em> | :Number The type of shortcut. See Enums.StatItemClass                                
</pre>

---

# [ function ] SlotPassiveRemoved

Signal sent when a shortcut has been removed. This will not be sent if the shortcut changes position, moved.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotDragEnd

# [ function ] GetMouseSlotID

# [ function ] GetAbilityColors

