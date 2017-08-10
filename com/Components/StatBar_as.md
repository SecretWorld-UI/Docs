# [ class ] com.Components.StatBar

the statbar components will extend any MovieClip tha statbar references two items,

---

# [ group ] Variables

# [ variable ] m_Dynel

# [ variable ] m_GroupElement

# [ variable ] m_Current

# [ variable ] i_StatText

# [ variable ] i_Bar

# [ variable ] m_Max

# [ variable ] m_CurrentFrame

# [ variable ] m_TargetFrame

# [ variable ] m_NameXOrgPos

# [ variable ] m_ShowStatText

# [ variable ] m_ShowStatTextAsPercent

# [ variable ] m_CurrentStatID

# [ variable ] m_MaxStatID

# [ variable ] m_FadeWhenInactive

# [ variable ] m_FadeTimer

# [ variable ] m_Fading

# [ variable ] m_AlwaysVisible

# [ variable ] m_FrameCount

# [ variable ] m_FrameResetHack

# [ variable ] m_CurrentFrameHack

# [ variable ] m_CurrentFrameHackMax

# [ group ] Functions

# [ function ] StatBar

# [ function ] Init

# [ function ] SetFadeWhenInactive

# [ function ] SetDynel

# [ function ] SetGroupElement

# [ function ] SlotCharacterEntered

# [ function ] SlotCharacterExited

# [ function ] ClearBar

# [ function ] SlotStatChanged

listens to a change in stats.

## Parameters

<pre>
<em>p_stat</em>  | :Number  -  The type of stat, defined in the Stat  Enum
<em>p_value</em> | :Number -  The value of the stat                       
</pre>

---

# [ function ] SetMax

Retrieves the maxhealt and creates a factor by dividing it with the number of frames in the active statbar, if max health is 0 remove the healthbar, othervise set the max health text

## Parameters

<pre>
<em>maxStat</em> | :String - the max stat as a string
</pre>

## Returns

void

---

# [ function ] UpdateStatText

# [ function ] SetCurrent

Updates the stat text and bar

## Parameters

<pre>
<em>stat</em> | :String - the health as a string
</pre>

## Returns

void

---

# [ function ] Update

# [ function ] onEnterFrame

# [ function ] UpdateStatBar

# [ function ] Hide

# [ function ] Show

# [ function ] SetShowText

# [ function ] OnFadeTimer

