# [ class ] GUI.Mission.MissionGoal

# [ group ] Variables

# [ variable ] m_Quest

# [ variable ] m_MissionId

# [ variable ] m_GoalPhase

# [ variable ] m_AlignRight

# [ variable ] m_GoalList

# [ variable ] m_GoalsAnimating

# [ variable ] m_CurrentlyDisplayedGoalIDs

# [ variable ] m_GoalTrackers

# [ variable ] SignalAnimationsDone

# [ group ] Functions

# [ function ] MissionGoal

# [ function ] SetData

# [ function ] Draw

# [ function ] GoalCreationAllowed

iterate and write the goal info

---

# [ function ] IsAnimationsPending

# [ function ] SlotGoalPhaseUpdated

when a phase is updated

---

# [ function ] SlotGoalTimeLimitChanged

# [ function ] TaskAdded

# [ function ] SlotGoalAnimationCompleted

when a goal has finished some internal tweening

---

# [ function ] SlotGoalAnimationStarted

when a goal is currently doing some animation add the id if its not there

---

# [ function ] SlotRemoveGoal

# [ function ] AlignText

