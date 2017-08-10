# [ file ] AbilityList.as

# [ group ] Variables

# [ variable ] FriendlyName

Code for all the logic in the AbilityList

---

# [ variable ] m_Spells

# [ variable ] m_NumSpells

# [ variable ] m_AbilityHeight

# [ variable ] m_AbilityWidth

# [ variable ] m_AbilityListOpenDValue

# [ variable ] m_PassiveListOpenDValue

# [ variable ] s_ResolutionScaleMonitor

# [ group ] Functions

# [ function ] onLoad

# [ function ] onResize

listener for stage resize

---

# [ function ] openAbilityList

Button click handler for opening and closing the AbilityList

---

# [ function ] openPassiveList

# [ function ] SlotAbilityListOpenValueChanged

# [ function ] SlotPassiveListOpenValueChanged

when the passive list is opened or closed, hide and show the Abilities tab

---

# [ function ] SlotReslolutionValueChanged

On changes to the resolution, update this.

---

# [ function ] OnSignalSpellUpdate

# [ function ] PopulateMenu

Populate s the menu

---

# [ function ] CreateScrollbar

method that creates the scrollbar this fires upon changes to the resolution and the screen size

---

# [ function ] OnScrollbarUpdate

when interacting with the scrollbar

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

# [ function ] RemoveScrollBar

position

---

# [ function ] CloseMenu

Fires when the abilitymenu is closed

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

# [ function ] onUnload

