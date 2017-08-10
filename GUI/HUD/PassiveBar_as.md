# [ file ] PassiveBar.as

# [ group ] Variables

# [ variable ] m_PassiveAbilitySlots

this is all the logic applying to the PassiveBar

---

# [ variable ] m_NumAbilities

# [ variable ] m_PassiveBarActive

# [ variable ] m_AbilityBarVisible

# [ variable ] SizeChanged

# [ variable ] ULTIMATE_ABILITY_UNLOCK

# [ variable ] m_UltimateProgress

# [ variable ] m_Character

# [ variable ] m_BaseWidth

# [ variable ] m_InitialY

# [ group ] Functions

# [ function ] onLoad

# [ function ] onUnload

check if the passives bar opens or closes

---

# [ function ] SlotAbilityBarVisibilityChanged

# [ function ] SlotStatChanged

# [ function ] SlotTagAdded

# [ function ] InitializeBar

sets up the empty PassiveAbilityslots, and if opened, opens the passive bar

---

# [ function ] SlotPassiveListOpenValueChanged

triggers when there is a change to the Passive Lists distributed value

---

# [ function ] SlotTogglePassiveBar

# [ function ] SlotShowPassivesBar

# [ function ] TogglePassiveBar

# [ function ] OpenPassiveBar

# [ function ] ClosePassiveBar

# [ function ] GetAllPassives

Gets all the equipped passives and

---

# [ function ] debugObject

# [ function ] SlotDragBegin

# [ function ] SlotDragEnd

# [ function ] GetMouseSlotID

# [ function ] SlotPassiveAdded

Signal sent when a shortcut has been added. This also happens when you teleport to a new pf. Note that you might get an SignalShortcutEnabled right afterward if the shortcut is disabled. And SignalCooldownTime if it's in cooldown.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotPassiveRemoved

Signal sent when a shortcut has been removed. This will not be sent if the shortcut changes position, moved.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotSwapBar

# [ function ] SlotRestoreSwapBar

# [ function ] RestoreSwapBar

# [ function ] CreateUltimateAbilityProgress

# [ function ] UpdateUltimateAbilityProgress

# [ function ] PulseUltimate

# [ function ] onLoadInit

# [ function ] SlotAbilityBarDrag

