# [ class ] GUI.Mission.MissionTrackerItem

# [ group ] Variables

# [ variable ] m_TierName

# [ variable ] m_TierNumbers

# [ variable ] m_MissionTimer

# [ variable ] m_BonusBG

# [ variable ] m_Quest

# [ variable ] m_QuestId

# [ variable ] m_EnableProgress

# [ variable ] m_Goals

# [ variable ] m_IsMissionJournalActive

# [ variable ] SignalSetAsMainMission

# [ variable ] SignalDoubleClicked

# [ variable ] SignalAnimationsDone

# [ variable ] NM_DIFFICULTY

# [ group ] Functions

# [ function ] MissionTrackerItem

# [ function ] configUI

# [ function ] GetMissionId

# [ function ] ShowProgress

# [ function ] SetData

# [ function ] SetGoalVisibility

# [ function ] Draw

# [ function ] DrawTierInfo

# [ function ] IsAnimationPending

# [ function ] TaskAdded

when a task is added to a parent that is present, see if there are goals animating if not just draw the new information

---

# [ function ] DispatchAnimationDone

# [ function ] IconDoubleClickHandler

# [ function ] IconClickHandler

# [ function ] AlignText

