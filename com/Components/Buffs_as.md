# [ class ] com.Components.Buffs

# [ group ] Variables

# [ variable ] m_BuffList

# [ variable ] m_MovieClipLoader

# [ variable ] m_Direction

# [ variable ] SizeChanged

# [ variable ] SignalBuffAdded

# [ variable ] SignalBuffRemoved

# [ variable ] m_UseTimers

# [ variable ] m_ShowCharges

# [ variable ] m_MaxPerLine

# [ variable ] m_NumLines

# [ variable ] m_Multiline

# [ variable ] BUFF

magics to control removal of buff debuffs

---

# [ variable ] DEBUFF

# [ variable ] ALL

# [ variable ] m_ShowBuff

# [ variable ] m_ShowDebuff

# [ variable ] m_Character

# [ variable ] m_GroupElement

# [ variable ] m_Width

# [ variable ] m_NeedSizeUpdate

# [ group ] Functions

# [ function ] Buffs

# [ function ] SetWidth

# [ function ] SetMultiline

# [ function ] SetCharacter

# [ function ] SetGroupElement

# [ function ] ClearAllBuffs

# [ function ] SlotCharacterEntered

# [ function ] SlotCharacterExited

# [ function ] AddExistingBuffs

# [ function ] ShowTimers

# [ function ] GetShowTimer

# [ function ] NoTimers

# [ function ] ShowCharges

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

# [ function ] GetBuffCount

# [ function ] AddBuff

# [ function ] SlotBuffAdded

disregard buffs if set to not show

---

# [ function ] SlotBuffRemoved

# [ function ] GetBuffClip

# [ function ] SetMaxPerLine

# [ function ] BuffCompare

SortOrder TrueBand -> Trigger -> Resistance -> Buff/Debuff (Sorted on timeleft)

---

# [ function ] Layout

