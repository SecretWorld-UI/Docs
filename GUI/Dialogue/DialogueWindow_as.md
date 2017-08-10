# [ class ] GUI.Dialogue.DialogueWindow

# [ group ] Variables

# [ variable ] MISSION_STATE_IN_PROGRESS

state enums

---

# [ variable ] MISSION_STATE_PAUSED

# [ variable ] MISSION_STATE_COOLDOWN

# [ variable ] MISSION_STATE_IDLE

# [ variable ] MISSION_STATE_LOCKED

# [ variable ] MISSION_STATE_COMPLETE_REPETABLE

# [ variable ] MISSION_STATE_DLC

# [ variable ] MOUSE_ACTION_OVER

# [ variable ] MOUSE_ACTION_OUT

# [ variable ] MOUSE_ACTION_DOWN

# [ variable ] ACTION_OPEN

# [ variable ] ACTION_DISABLED

# [ variable ] ACTION_ENABLE

# [ variable ] ACTION_DISABLE

# [ variable ] ACTION_OPEN_AND_ENABLE

# [ variable ] NM_DIFFICULTY

# [ variable ] m_DynelName

# [ variable ] m_MissionClip

# [ variable ] m_MissionList

# [ variable ] m_DialogueClip

# [ variable ] m_QuestionClips

# [ variable ] m_Questions

# [ variable ] m_Depths

# [ variable ] m_DynelID

# [ variable ] m_LockToScreen

# [ variable ] m_ResolutionScaleMonitor

# [ variable ] m_Dynel

# [ variable ] m_Character

# [ variable ] m_QuestGiver

# [ variable ] m_IsDialogueStarted

# [ variable ] m_IsDialogueOpen

# [ variable ] m_HasReceivedQuestions

# [ variable ] m_CurrentDialoguePlaying

# [ variable ] m_IsOpeningInProgress

# [ variable ] m_OpenTimer

# [ variable ] m_WasOpen

# [ variable ] m_AnimationDuration

# [ variable ] m_TweenDuration

# [ variable ] m_ShowNames

# [ variable ] m_OpenMissionID

# [ variable ] m_IconSizes

# [ variable ] m_IconSize

# [ variable ] m_IconTotal

# [ variable ] m_MaxScale

# [ variable ] m_TotalSelectorHeight

# [ variable ] m_MinAlpha

# [ variable ] m_MaxAlpha

# [ variable ] m_NormalScale

# [ variable ] m_MinScale

# [ variable ] m_ClipYAnchor

# [ variable ] m_MaxSizedIconX

# [ variable ] m_MissionThrottleIntervalId

# [ variable ] m_MissionThrottleInterval

# [ variable ] m_EnableInterval

# [ variable ] m_PowerRank

# [ variable ] m_Level

# [ variable ] m_Shadow

# [ variable ] m_HeadlineTextFormat

# [ variable ] m_ActionTextFormat

# [ variable ] m_TimerTextFormat

# [ variable ] m_CurrentDialogueMask

# [ variable ] m_LoadingSymbol

# [ variable ] m_ShowWindow

# [ variable ] m_IsMember

# [ variable ] m_EscapeNode

# [ group ] Functions

# [ function ] DialogueWindow

# [ function ] configUI

# [ function ] onUnload

# [ function ] onMousePress

# [ function ] SlotStatUpdated

# [ function ] SlotMemberStatusUpdated

# [ function ] SlotVoiceStarted

# [ function ] SlotVoiceFinished

tell all conversations the to disable until the ongoing is done

---

# [ function ] SlotVoiceAborted

tell all conversations the chitchat is done

---

# [ function ] GetVoiceEntry

# [ function ] onEnterFrame

# [ function ] LockToScreen

# [ function ] IsLocked

# [ function ] EscapePressed

# [ function ] SlotEnteredReticuleMode

# [ function ] OpenFirstIncompleteMission

# [ function ] UpdateWindow

# [ function ] SetMissionThrottle

hide and disable clicks on the missionWindow if it is blocked

---

# [ function ] AnimateUnusedMissions

calls a throttle effect on missions you have not yet had

---

# [ function ] ToggleDialogue

# [ function ] CheckOpenDialogue

# [ function ] OpenDialogue

# [ function ] CloseDialogue

# [ function ] CloseDialogueContent

# [ function ] CleanDialogue

# [ function ] EndConversation

# [ function ] SetQuestions

# [ function ] SetTopicDepths

# [ function ] FillQuestions

# [ function ] SlotQuestionChosen

# [ function ] ClearQuestions

# [ function ] SlotMissionCompleted

# [ function ] SlotQuestAvailable

# [ function ] SlotTaskAdded

# [ function ] SlotQuestCooldownChanged

# [ function ] SlotTierRemoved

# [ function ] SlotQuestEvent

# [ function ] SlotQuestChanged

# [ function ] SlotTagAdded

# [ function ] SlotTagsReceived

# [ function ] Clear

# [ function ] Draw

# [ function ] CheckHide

# [ function ] RedrawMissions

# [ function ] DrawDialogue

# [ function ] DrawMissions

# [ function ] QuestCompare

Add clips

---

# [ function ] ClearMissions

# [ function ] GetMissionState

returns the current state of the mission

---

# [ function ] IsMissionValid

Checks if a given id is a valid quest (to see if it was not removed)

## Parameters

<pre>
<em>is</em> | :Number -  the quest id to validate
</pre>

## Returns

boolean, true if quest is valid

---

# [ function ] IsMissionCompleted

# [ function ] CreateSingleSelector

attaches an instance of the Selector library item to the i_Frame and populates it with data from the Quests.m_AvailableTiers object

---

# [ function ] SlotMissionIconClicked

mouse events

---

# [ function ] CooldownFrameHandler

# [ function ] AddIconModifier

# [ function ] GetActionText

# [ function ] MoveButtonPlayhead

For the selectorbutton, moves the playhead

## Parameters

<pre>
<em>button</em>   | :MovieClip - the button to update                          
<em>action</em>   | :Number - the action to perform, opne, close ...           
<em>isActive</em> | :Boolean - is the mission type active                      
<em>state</em>    | :Number - the state of the mission, paused, in progress....
</pre>

---

# [ function ] IsMissionOpen

# [ function ] CloseAllMissionClips

# [ function ] AnimateSelector

Fires when a mission icon from the mission selector interface has been clicked can and will be optimised. But not  today

---

# [ function ] ToggleOpeningProgress

iterate and set the m_OpenMissionId to the selected id

---

# [ function ] CooldownLayout

# [ function ] Animate

