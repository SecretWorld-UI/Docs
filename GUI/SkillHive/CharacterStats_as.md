# [ class ] GUI.SkillHive.CharacterStats

# [ group ] Variables

# [ variable ] m_StatPageItems

objects

---

# [ variable ] m_LabelObject

# [ variable ] m_StatPagesObject

# [ variable ] m_CharacterStatsPane

# [ variable ] m_ContentClip

# [ variable ] m_StatPage

# [ variable ] m_CurrentStatPageIndex

# [ variable ] m_PanelTweenSpeed

# [ variable ] m_StatPageItemHeight

layoup

---

# [ group ] Functions

# [ function ] CharacterStats

# [ function ] SetCharacterName

# [ function ] SetFactionName

# [ function ] CreatePaperDoll

# [ function ] CreateStatPage

Attaches a dropdown to the m_StatPage MovieClip and draws the stats on it when requested

---

# [ function ] SlotCharacterLoaded

# [ function ] UpdateStatPage

Updates the content of the stat page when a new page is selected

## Parameters

<pre>
<em>index</em> | :Number - the index in the m_StatPageItems to load
</pre>

---

# [ function ] OnDropdownSelection

updates the statpage wnhen a new item is selected from the dropdown

## Parameters

<pre>
<em>event</em> | :Object - The Scaleform event object containing type and target
</pre>

---

# [ function ] SlotSkillUpdated

when an update to a skill is received checks if the stat is visible and writes to it, if not it stores the updated skill

## Parameters

<pre>
<em>updatedSkill</em> | :Number - the id of the skill to update
</pre>

---

