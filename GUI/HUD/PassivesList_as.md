# [ file ] PassivesList.as

# [ group ] Variables

# [ variable ] m_AbilityListOpenDValue

# [ variable ] m_Spells

# [ variable ] m_NumSpells

# [ variable ] m_ItemHeight

# [ variable ] m_ItemWidth

# [ group ] Functions

# [ function ] onLoad

# [ function ] openPassivesTab

call whatever when clicking teh passives tab

---

# [ function ] openAbilityTab

opens teh abilitybar, just swapping the existing values and let the signals move everything

---

# [ function ] CloseMenu

Fires when the abilitymenu is closed

---

# [ function ] SlotPassivesListOpenValueChanged

Updates the distributet value that is used to create

---

# [ function ] onAbilityListOpenValueChanged

triggers when the abilitylist gets opened or closed (can only have one open at the time)

---

# [ function ] OnSignalPassiveUpdate

# [ function ] PopulateMenu

Populate s the menu

---

# [ function ] CreateSingleSpell

Creates a new icon from the spell object by attaching the icon button and then load the correct icon graphics onto it

## Parameters

<pre>
<em>i</em> | :Number index in the m_SpellArray where the spellobject is retrieved
</pre>

## Returns

mainClip:MovieClip - the newly created clip

---

# [ function ] SetupDragClip

Creates the icon that will be dragged when equipping an ability

## Parameters

<pre>
<em>clip</em> | :MovieClip - the clip to duplicate and
</pre>

## Returns

MovieClip - a new movieclip identical to the icon selected for dragging

---

# [ function ] OnDragEnd

load the icon on to the newly created icon background

---

