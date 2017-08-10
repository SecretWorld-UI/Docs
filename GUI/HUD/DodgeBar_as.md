# [ file ] DodgeBar.as

# [ group ] Variables

# [ variable ] m_IntervalId

All logic for the castbar

---

# [ variable ] m_Increments

# [ variable ] m_TotalFrames

# [ variable ] m_StopFrame

# [ variable ] m_ProgressBarType

# [ variable ] m_DodgeBuffSpellID

# [ variable ] m_Character

# [ variable ] m_BuffStartTime

# [ variable ] m_BuffDuration

# [ variable ] m_EditModeMask

# [ group ] Functions

# [ function ] Init

# [ function ] onUnload

# [ function ] SetCharacter

# [ function ] SlotBuffAdded

Signal sent when a command is started.

## Parameters

<pre>
<em>name</em>            | :String    The name of the command.                                                                                                                       
<em>progressBarType</em> | :The type of progressbar _global.Enums.CommandProgressbarType.e_CommandProgressbar_Fill or _global.Enums.CommandProgressbarType.e_CommandProgressbar_Empty
</pre>

---

# [ function ] ExecuteCallback

# [ function ] SlotBuffUpdated

# [ function ] SlotBuffRemoved

# [ function ] ResizeHandler

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

