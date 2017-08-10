# [ class ] GUI.HUD.AbilitySlot

Object that controls an ability,

---

# [ group ] Variables

# [ variable ] SWAP_ANIMATION_DURATION

# [ variable ] m_IsActive

# [ variable ] m_IconPath

# [ variable ] m_HitPos

# [ variable ] m_IsBeingDragged

# [ variable ] m_ColorLine

# [ variable ] m_DisabledColor

# [ variable ] m_SlotMC

# [ variable ] m_SlotId

# [ variable ] m_Icon

# [ variable ] m_WasHit

# [ variable ] m_IsUnderMouse

# [ variable ] m_Tooltip

# [ variable ] m_TooltipTimeout

# [ variable ] m_UseEffects

# [ variable ] m_ResourceGenerator

# [ variable ] m_Ability

# [ variable ] m_SwappedAbility

# [ variable ] m_Reflection

# [ variable ] m_Enabled

# [ variable ] m_RangedEnabled

# [ variable ] m_IsCooldown

# [ variable ] m_DragType

# [ variable ] m_LinkageId

# [ variable ] m_SpellType

# [ variable ] m_Id

# [ variable ] m_ShowAugments

# [ group ] Functions and Properties

# [ function ] AbilitySlot

# [ function ] OnMouseUp

# [ function ] OnMouseDown

# [ function ] GetTooltipData

# [ function ] GetAugmentData

# [ function ] StartTooltipTimeout

# [ function ] StopTooltipTimeout

# [ function ] CloseTooltip

# [ function ] OpenTooltip

# [ function ] OnMouseOver

# [ function ] OnMouseOut

# [ function ] OnDragOut

# [ function ] OnUnload

# [ function ] OnMouseMove

# [ function ] SlotItemDroppedOnDesktop

# [ function ] SlotDragHandled

# [ function ] CanDragAbility

# [ function ] SetAbilityData

sets up the visuals for the ability

## Parameters

<pre>
<em>p_icon</em>      | :String  - the rdb id of the icon                           
<em>p_ColorLine</em> | :Number - id of the colour, no real value                   
<em>spellType</em>   | :Number - the spelltype, used to identify elite abilities   
<em>linkageId</em>   | :String - Linkage name in the library for the ability icon  
<em>useEffects</em>  | :Boolean - wether or not to display effects (reflections...)
</pre>

---

# [ function ] SwapAbilityData

# [ function ] Clear

clears the class intance of all variables that needs to be nulled when the class is reset

## Returns

void

---

# [ function ] AddEffects

# [ function ] RemoveEffects

# [ function ] UpdateAlpha

# [ function ] RemoveIcon

when an ability is removed from the slot, the ability is cleared from the AbilitySlot

---

# [ function ] SetVisible

# [ function ] GetSlotId

# [ property ] Slot

# [ function ] SwapEffect

# [ function ] SwapBackTimerEffect

# [ property ] Ability

# [ property ] IsActive

