# [ class ] GUI.Mission.MissionGoalItem

# [ group ] Variables

# [ variable ] m_GoalNameWidth

# [ variable ] m_GoalNameAnim

# [ variable ] m_GoalNumAnim

# [ variable ] m_GoalProgressCursor

# [ variable ] m_GoalCompleteCursor

# [ variable ] m_GoalFailedCursor

# [ variable ] m_Timer

# [ variable ] m_IsAnimating

# [ variable ] m_IsComplete

# [ variable ] m_IsFailed

# [ variable ] m_GoalProgressAnimationActive

# [ variable ] m_SolvedTimes

# [ variable ] m_RepeatCount

# [ variable ] m_AlignRight

# [ variable ] m_DesiredY

# [ variable ] m_WillTimeoutSucceed

# [ variable ] m_GoalNumSwitchNumbersFrame

# [ variable ] m_GoalProgressEnableNumbersFrame

# [ variable ] m_GoalCompleteTweenNameFrame

# [ variable ] m_MaxNameWidth

# [ variable ] SignalGoalAnimationCompleted

# [ variable ] SignalGoalAnimationStarted

# [ variable ] SignalGoalCompleted

# [ variable ] m_QueuedProgress

# [ variable ] m_UID

# [ variable ] m_GoalID

# [ variable ] m_Goal

# [ variable ] m_TierID

# [ group ] Functions

# [ function ] MissionGoalItem

# [ function ] configUI

# [ function ] ForceGoalComplete

sometimes a goal is completed (tier or mission completes but forgets to tell the goal) this is a fallback, manually calling the Goal complete

---

# [ function ] WillSelfDetruct

will this goal item self destruct after animation is done?

---

# [ function ] SetData

# [ function ] Draw

# [ function ] SlotGoalProgress

# [ function ] SlotTierFailed

Remove any other progressindicators running

---

# [ function ] SlotGoalFinished

Remove any other progressindicators running

---

# [ function ] RemoveProgressCursor

Remove any other progressindicators running

---

# [ function ] GoalProgressFrameMonitor

dispatches a signal after the animation is done,

---

# [ function ] GoalNumFrameMonitor

# [ function ] GoalFailedFrameMonitor

dispatches a signal after the animation is done,

---

# [ function ] GoalCompleteFrameMonitor

dispatches a signal after the animation is done,

---

# [ function ] GoalNameFrameMonitor

when the goal completed animation is finished

---

# [ function ] AlignText

