# [ class ] GUI.HUD.ActiveAbilitySlot

# [ group ] Variables

# [ variable ] s_HighestSlotDepth

# [ variable ] m_State

# [ variable ] m_SlotSize

# [ variable ] m_Ability

# [ variable ] m_Reflection

# [ variable ] m_QueueAnimation

# [ variable ] m_IsChanneling

# [ variable ] m_CanUse

# [ group ] Functions

# [ function ] ActiveAbilitySlot

# [ function ] OnMouseUp

# [ function ] SetCanUse

# [ function ] AddEffects

# [ function ] RemoveEffects

# [ function ] SwapEffect

# [ function ] SwapBackTimerEffect

# [ function ] CleanupAfterAnimation

# [ function ] SwapBackEffect

# [ function ] VerticalFlipBackEffect

# [ function ] VerticalFlipEffect

# [ function ] Fire

# [ function ] AddToQueue

add animation here.

---

# [ function ] RemoveFromQueue

# [ function ] Use

# [ function ] UpdateAbilityFlags

# [ function ] StartChanneling

# [ function ] StopChanneling

# [ function ] AddCooldown

adds a cooldown to the ability by attaching tha cooldown animation to the slot and passing it to the timer the ability cooldown uses the AbilityCooldown and the Timer to create a "refill" effect and a countdown timer

---

# [ function ] RemoveCooldown

remnoves a cooldown unconditionally

---

# [ function ] SetVisible

# [ function ] RemoveIcon

when an ability is removed from the slot, the ability is cleared from the AbilitySlot

---

# [ function ] GetTooltipData

# [ function ] SlotItemDroppedOnDesktop

# [ function ] IsChanneling

