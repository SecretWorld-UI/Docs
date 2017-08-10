# [ file ] Buff.as

# [ group ] Variables

# [ variable ] m_Slot

# [ variable ] m_BuffList

# [ variable ] m_moviecliploader

# [ variable ] m_IntervalId

# [ variable ] m_Direction

# [ variable ] SizeChanged

# [ variable ] m_UseTimers

# [ variable ] m_ShowCharges

# [ variable ] m_TDB_Cancelbuff

# [ variable ] m_TDB_QuestionMark

# [ variable ] m_Tooltip

# [ variable ] m_TooltipBuffID

# [ variable ] BUFF

magics to control removal of buff debuffs

---

# [ variable ] DEBUFF

# [ variable ] ALL

# [ variable ] m_ShowBuff

# [ variable ] m_ShowDebuff

# [ variable ] m_Character

# [ variable ] m_GroupElement

# [ group ] Functions

# [ function ] Init

# [ function ] SetCharacter

# [ function ] SetGroupElement

# [ function ] ClearAllBuffs

# [ function ] SlotCharacterEntered

# [ function ] AddExistingBuffs

# [ function ] onUnload

# [ function ] NoTimers

# [ function ] NoCharges

# [ function ] ShowBuffs

# [ function ] ShowDebuffs

# [ function ] SetDirectionDown

# [ function ] ClearBuffs

clears all buffs from the visuals

## Parameters

<pre>
<em>type</em> | :Number - BUFF, DEBUFF or ALL depending on what you want to remove
</pre>

## Returns

Void

---

# [ function ] ShowAllBuffs

todo implement method to request all buffs on a dynel enables all buffs if these have not been showed

## Returns

Void

---

# [ function ] AddBuff

# [ function ] CloseTooltip

do not scale an icon if it has been scaled before

---

# [ function ] SlotBuffAdded

# [ function ] SlotBuffRemoved

# [ function ] SlotCancelBuff

# [ function ] GetBuffClip

# [ function ] TimerCallback

# [ function ] Layout

