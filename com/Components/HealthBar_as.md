# [ class ] com.Components.HealthBar

# [ group ] Variables

# [ variable ] STATTEXT_PERCENT

# [ variable ] STATTEXT_NUMBER

# [ variable ] AEGIS_PSYCHIC

# [ variable ] AEGIS_TECH

# [ variable ] AEGIS_DEMONIC

# [ variable ] m_Dynel

# [ variable ] m_GroupElement

# [ variable ] m_Character

# [ variable ] m_CurrentStatID

# [ variable ] m_MaxStatID

# [ variable ] m_BoostStatID

# [ variable ] m_PinkShieldStatID

# [ variable ] m_BlueShieldStatID

# [ variable ] m_RedShieldStatID

# [ variable ] m_PinkShieldAbsoluteStatID

# [ variable ] m_BlueShieldAbsoluteStatID

# [ variable ] m_RedShieldAbsoluteStatID

# [ variable ] m_PinkShieldPercentStatID

# [ variable ] m_BlueShieldPercentStatID

# [ variable ] m_RedShieldPercentStatID

# [ variable ] m_PlayerShieldTypeStatID

# [ variable ] m_PlayerShieldCurrentStatID

# [ variable ] m_PlayerShieldMaxStatID

# [ variable ] m_AegisDamageTypeStatID

# [ variable ] m_ShieldsOnTop

# [ variable ] m_Max

# [ variable ] m_Current

# [ variable ] m_Boost

# [ variable ] m_BoostMask

# [ variable ] m_Text

# [ variable ] m_Bar

# [ variable ] m_ShieldBar

# [ variable ] m_SecondShield

# [ variable ] m_ThirdShield

# [ variable ] m_AegisDamageType

# [ variable ] m_AlwaysVisible

# [ variable ] m_IsPlayer

# [ variable ] m_ShowText

# [ variable ] m_TextType

# [ variable ] m_TweenTime

# [ variable ] m_TweenLimitPercent

# [ variable ] m_ShowHPUnderAegis

# [ variable ] m_ShowAegisValues

# [ group ] Functions

# [ function ] HealthBar

# [ function ] SetDynel

trace("healthbar initiated")

---

# [ function ] SlotCharacterEntered

# [ function ] SlotCharacterExited

# [ function ] SetBarScale

sets the scaling of the bar and repositions the textfield, this will also scale the textfield (uniformly) based on the input

## Parameters

<pre>
<em>xscale</em>    | :Number - The xscale                                              
<em>yscale</em>    | :Number - the yscale                                              
<em>scaleText</em> | :Number [opt] -the scale of text, if omitted no scaling will occur
</pre>

---

# [ function ] SetGroupElement

# [ function ] SetCharacter

# [ function ] ClearBar

trace("SetCharacter "+character)

---

# [ function ] SlotStatChanged

listens to a change in stats.

## Parameters

<pre>
<em>p_stat</em>  | :Number  -  The type of stat, defined in the Stat  Enum
<em>p_value</em> | :Number -  The value of the stat                       
</pre>

---

# [ function ] SetMax

gets tha max and sets this as a member used to calculate the percent of health left (0 - 100, used for the _xscale)

## Parameters

<pre>
<em>maxStat</em> | :String - the max stat as a string
</pre>

## Returns

void

---

# [ function ] SetCurrent

Updates the stat text and bar

## Parameters

<pre>
<em>stat</em> | :String - the health as a string
</pre>

## Returns

void

---

# [ function ] UpdateEnemyShields

# [ function ] UpdateCurrentEnemyShield

# [ function ] UpdatePlayerShields

# [ function ] UpdateStatText

Updates the text that overlays the healthbar updates it as percent or real numbers

---

# [ function ] UpdateStatBar

# [ function ] UpdateAegisDamageType

# [ function ] Hide

# [ function ] Show

# [ function ] SetShowText

show the text

## Parameters

<pre>
<em>showText</em> | :Boolean - Show the text or not
</pre>

---

# [ function ] SetTextType

How to display the text, as numbers or percent

## Parameters

<pre>
<em>textType</em> | :Number - How is the text displayed, using the static HealtBar.STATTEXT_...
</pre>

---

# [ function ] PositionUpcomingShields

# [ function ] SetShieldsOnTop

