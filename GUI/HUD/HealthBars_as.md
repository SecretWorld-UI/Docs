# [ file ] HealthBars.as

# [ group ] Variables

# [ variable ] m_Slot

# [ variable ] m_DynelSlot

# [ variable ] m_CurrentHealth

# [ variable ] m_MaxHealth

# [ variable ] m_Target

# [ variable ] m_NameXOrgPos

# [ group ] Functions

# [ function ] Init

# [ function ] SetSlot

# [ function ] onDynelOnClient

# [ function ] onSlotChanged

when a slot is changed. Match the target to  a target enum and update as neccessary.

## Parameters

<pre>
<em>p_Slot</em>   | :Number  - The slot enum as defined under DynelSlot in ASEnums
<em>p_Exists</em> | :Booelan - True if the slot has a dynel.                      
</pre>

---

# [ function ] onStatUpdated

listens to a change in stats.

## Parameters

<pre>
<em>p_stat</em>  | :Number  -  The type of stat, defined in the Stat  Enum
<em>p_value</em> | :Number -  The value of the stat                       
</pre>

---

# [ function ] SetMaxHealth

Retrieves the maxhealt and creates a factor by dividing it with the number of frames in the active healthbar, if max health is 0 remove the healthbar, othervise set the max health text

## Parameters

<pre>
<em>p_maxhealth</em> | :String - the max health as a string
</pre>

## Returns

void

---

# [ function ] UpdatePercent

# [ function ] UpdateHealth

Updates the health text and bar

## Parameters

<pre>
<em>p_health</em> | :String - the health as a string
</pre>

## Returns

void

---

# [ function ] SlotNewTeamLeader

# [ function ] AddStar

# [ function ] RemoveStar

# [ function ] ResizeHandler

