# [ class ] GUI.Mission.MissionTimer

# [ group ] Variables

# [ variable ] m_UpdateSpeed

# [ variable ] m_IntervalId

# [ variable ] m_ThrottleCounter

# [ variable ] m_EndTime

# [ variable ] textField

# [ variable ] i_Back

# [ variable ] m_MinWidth

# [ variable ] m_IsColorized

# [ variable ] m_StartThrottleAt

# [ variable ] m_ChriticalWarningAt

# [ variable ] m_Destructor

# [ variable ] m_IsSuccessOnCompletion

# [ variable ] m_TimeoutColor

# [ group ] Functions

# [ function ] MissionTimer

# [ function ] SetTimer

sets the timer and starts it

## Parameters

<pre>
<em>param</em> |   timestamp:Numbing       the gametime when the timer completes              
<em>param</em> |   firstWarning:Number     MS before end where the thing should start flashing
<em>param</em> |   criticalWarning:Number  MS before end where the timer changes color        
</pre>

---

# [ function ] SetSuccessType

sets a flag defining if the completed timer will result in success or fail (this will be used to determine) if the flashing missions at the end will flash green or red

## Parameters

<pre>
<em>param</em> |   isSuccessOnCompletion:Boolean 
</pre>

---

# [ function ] UpdateBorder

# [ function ] TimerCallback

# [ function ] SlotInstanceDying

