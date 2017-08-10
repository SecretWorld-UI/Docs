# [ file ] MissionTracker.as

# [ group ] Variables

# [ variable ] m_GuiModeMonitor

# [ variable ] m_IsMissionJournalActive

# [ variable ] m_VisibilityMonitor

# [ variable ] m_ActiveMission

# [ variable ] m_MissionTrackerItem

# [ variable ] m_BonusTrackerItem

# [ variable ] m_HitArea

# [ variable ] m_MissionBar

# [ variable ] m_IsBarActive

# [ variable ] m_LastCompletedMission

# [ variable ] m_IsDragIconHighlighted

# [ variable ] m_IsDraggingIcon

# [ variable ] m_AlignRight

# [ variable ] m_ForceShowMissionTrackerValue

# [ variable ] m_ForceShowMissionTracker

# [ variable ] m_ActiveQuestIDValue

# [ variable ] m_ForceReportsButton

# [ variable ] m_ReportsButton

# [ variable ] m_EditModeMask

# [ variable ] m_MissionTypeTextFormat

# [ variable ] SLOT_STORY

# [ variable ] SLOT_DUNGEON

# [ variable ] SLOT_MAIN

# [ variable ] SLOT_INVESTIGATION

# [ variable ] SLOT_SIDE_1

# [ variable ] SLOT_SIDE_2

# [ variable ] SLOT_SIDE_3

# [ variable ] SLOT_COUNT

# [ variable ] FUSANG_PROJECTS_ID

# [ variable ] PROGRESS_PING_TIME

# [ variable ] m_MissionTrackerItemArray

# [ variable ] m_MissionTypeArray

# [ variable ] m_MissionOutline

# [ variable ] m_ProgressPingTimer

# [ group ] Functions

# [ function ] onLoad

# [ function ] onUnload

# [ function ] SlotClientCharacterAlive

# [ function ] CreateSlotTooltips

# [ function ] CreateSlotAnimations

# [ function ] AddSingleTooltip

# [ function ] FocusBarIn

# [ function ] SlotForceShowMissionTracker

# [ function ] SlotHighlightSlot

# [ function ] HighlightMission

# [ function ] SlotCharacterEnteredReticuleMode

# [ function ] SlotCharacterExitedReticuleMode

# [ function ] MissionBarFocus

# [ function ] ShowMissionTracker

# [ function ] ShowNextMission

# [ function ] CheckBonusMission

# [ function ] SortByMissionType

# [ function ] ShowAllMissions

# [ function ] RemoveAllMissions

# [ function ] ShowMission

# [ function ] ShowBonusMission

# [ function ] OpenMissionJournal

# [ function ] GetMissionSlot

# [ function ] GetMission

# [ function ] IconDoubleClickHandler

# [ function ] SlotTaskAdded

When a new mission has been spawned, shift focus to this

---

# [ function ] SlotGoalProgress

# [ function ] ProgressPingTimeout

# [ function ] ClearProgressPingTimer

# [ function ] SlotQuestChanged

# [ function ] SlotMissionCompleted

# [ function ] SlotMissionRemoved

# [ function ] RemoveBonusMission

# [ function ] RemoveMainMission

# [ function ] SlotMissionRewardsAnimationDone

# [ function ] DrawReportButton

checks if there are any unsent reports and draws the report button if not

---

# [ function ] RemoveMissionReportButton

if there is a button present

---

# [ function ] SlotGuiModeChanged

# [ function ] SlotActiveQuestChanged

# [ function ] SlotVisibilityChanged

# [ function ] SlotMissionReportWindowClosed

when all MissionRewardWindows has been closed, dispatch this to see if we need to redraw the windows

---

# [ function ] IconMouseDragHandler

# [ function ] IconMouseOverCharacter

# [ function ] IconMouseOutCharacter

# [ function ] SlotObjectUnderMouseChanged

# [ function ] SlotDragEnd

# [ function ] AlignMissionTypes

# [ function ] AlignMissionItems

# [ function ] AlignText

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

