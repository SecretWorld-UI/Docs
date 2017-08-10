# [ class ] GUI.SkillHive.SkillhiveActiveAbilityBar

# [ group ] Variables

# [ variable ] m_AbilitySlots

# [ variable ] m_AugmentSlots

# [ variable ] SignalToggleVisibility

# [ variable ] m_AuxilliarySlotAchievement

# [ variable ] AUGMENT_SLOT_ACHIEVEMENT

# [ variable ] DAMAGE_AUGMENT_BIT

# [ variable ] HEALING_AUGMENT_BIT

# [ variable ] SURVIVABILITY_AUGMENT_BIT

# [ variable ] SUPPORT_AUGMENT_BIT

# [ group ] Functions

# [ function ] SkillhiveActiveAbilityBar

# [ function ] onLoad

# [ function ] onUnload

connect the signals

---

# [ function ] SlotTagAdded

# [ function ] GetTopFrameHeight

# [ function ] SlotToggleVisibility

# [ function ] EquipAugment

# [ function ] EquipActive

# [ function ] UnEquipActive

# [ function ] HighlightSlot

# [ function ] StopHighlightSlot

# [ function ] SlotShortcutAdded

Signal sent when a shortcut has been added. This also happens when you teleport to a new pf. Note that you might get an SignalShortcutEnabled right afterward if the shortcut is disabled. And SignalCooldownTime if it's in cooldown.

## Parameters

<pre>
<em>itemPos</em>   | :Number   The position the item was added to. This is used for refering to this item.
<em>name</em>      | :String      The name of the item in LDB format.                                     
<em>icon</em>      | :String      The icon resource information.                                          
<em>itemClass</em> | :Number The type of shortcut. See Enums.StatItemClass                                
</pre>

---

# [ function ] ValidateAugments

# [ function ] SlotShortcutRemoved

Signal sent when a shortcut has been removed. This will not be sent if the shortcut changes position, moved.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotShortcutMoved

Signal sent when a shortcut has been move to some other spot. No add/remove signal will be triggered.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position the item was move from.
<em>toPos</em>   | :Number     The position the item was move to.
</pre>

---

# [ function ] SlotShortcutEnabled

Signal sent when a shortcut is enabled/disabled. Will also be send when you enter a new playfield.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Number   0=disable, 1=enabled     
</pre>

---

# [ function ] CanAddShortcut

# [ function ] SlotDragEnd

# [ function ] GetMouseSlotID

# [ function ] GetAbilityColors

# [ function ] GetAugmentColors

# [ function ] ToggleHighlightTopFrame

