# [ class ] GUI.MissionJournal.JournalWindow

# [ group ] Variables

# [ variable ] m_ResolutionScaleMonitor

# [ variable ] m_Missions

# [ variable ] m_ExpandedTiersArray

# [ variable ] m_Level

# [ variable ] m_Character

# [ variable ] m_IsMember

# [ variable ] m_ContentSize

# [ variable ] m_MissionDescFormat

# [ variable ] m_HeaderNameFormat

# [ variable ] m_HeaderSubTextFormat

# [ variable ] m_HeaderTimerTextFormat

# [ variable ] m_GoalFormat

# [ variable ] m_CashFormat

# [ variable ] m_DropDownFormat

# [ variable ] m_TooltipTextFormat

# [ variable ] m_DebugFormat

# [ variable ] m_ExpandedMissionID

# [ variable ] m_TooltipController

# [ variable ] m_TooltipTimeoutId

# [ variable ] m_CinematicAudioHandle

# [ variable ] m_DeltaMultiplier

# [ variable ] m_IsResizing

controllers

---

# [ variable ] m_NeedRedraw

# [ variable ] m_DropdownHeight

Window Layout

---

# [ variable ] m_ScrollBarArchivedPosition

General Positioning

---

# [ variable ] m_TDB_Tier

Strings

---

# [ variable ] m_TDB_Tier_MixedCase

# [ variable ] m_TDB_AllRegions

# [ variable ] m_TDB_CurrentMisionons

# [ variable ] m_TDB_FinishedMissions

# [ variable ] m_TDB_AbandonedMissions

# [ variable ] m_TDB_PlayAudio

# [ variable ] m_TDB_PlayVideo

# [ variable ] m_TDB_ShowImage

# [ variable ] m_ScrollBar

# [ variable ] m_Mask

# [ variable ] m_Content

# [ variable ] m_Menu

# [ variable ] m_Background

# [ variable ] m_DeleteMissionButton

# [ variable ] m_ShareButton

# [ variable ] m_LocationButton

# [ variable ] m_PauseMissionButton

# [ variable ] m_MissionDropdown

# [ variable ] m_CloseButton

# [ variable ] m_JournalTypeIndexSelected

# [ variable ] m_JournalTypeCurrentMissionIndex

# [ variable ] m_JournalTypeFinishedMissionIndex

# [ variable ] m_JournalTypeAbandonedMissionIndex

# [ variable ] m_PlayfieldDropdown

# [ variable ] m_PlayfieldNames

# [ variable ] m_PlayfieldIndexSelected

# [ variable ] m_LastPlayfieldNameSelected

# [ variable ] NM_DIFFICULTY

# [ group ] Functions

# [ function ] JournalWindow

# [ function ] SetModuleData

# [ function ] GetModuleData

# [ function ] onEnterFrame

# [ function ] SetRedrawFlag

# [ function ] SetSize

# [ function ] GetSize

# [ function ] configUI

INSTANCIATION

---

# [ function ] SlotMemberStatusUpdated

goal info

---

# [ function ] SlotStatUpdated

# [ function ] CreateInitialWindow

# [ function ] OnJournalTypeSelection

dropdowns

---

# [ function ] OnPlayfieldSelection

hide the playfield selector if necessary

---

# [ function ] SetSelectedPlayfieldIndex

# [ function ] AreRewardsVisible

# [ function ] AttachDropdown

param name:String - the instance name of the new clip

## Parameters

<pre>
<em>contentArray</em>  | :Array - the dataprovider with the values for the dropdown
<em>parent</em>        | :MovieClip - the context / scope where the clip is created
<em>selectedIndex</em> | :Number - the selected index when creating the dropdown   
</pre>

## Returns

dropDowm:MovieClip - reference to the newly crated dropdown

---

# [ function ] FindMissionByID

# [ function ] FindCurrentTier

# [ function ] CreateSingleMissionClip

Create the header for each Mission Tier with buttons and methods for expanding

## Parameters

<pre>
<em>param</em> |   parent:MovieClip - reference to the journal window                 
<em>param</em> |   mission:com.GameInterface.Quest) - the mission object for this item
</pre>

## Returns

MovieClip - reference to the clip created in this method 

---

# [ function ] SetupButton

Invisible button for main textfield, sub textfiend and difficult display

---

# [ function ] CreateOpenMission

# [ function ] CreateRewards

draw the surrounding frame

---

# [ function ] CreateSingleTierClip

# [ function ] CreateSingleGoal

# [ function ] UpdateMissionDropdownBoxes

numbers.. (x / y)

---

# [ function ] Redraw

Abandoned quests

---

# [ function ] CompareMissions

add scrollbar

---

# [ function ] MediaButtonHandler

# [ function ] CloseWindowHandler

# [ function ] TrashcanHandler

# [ function ] PauseHandler

# [ function ] ShareHandler

# [ function ] CinematicAudioHandler

# [ function ] LocationHandler

# [ function ] OnScrollbarUpdate

# [ function ] SetExpandedMissionID

# [ function ] TierNameClickHandler

# [ function ] ToggleExpandMissionEventHandler

# [ function ] ToggleExpandMission

# [ function ] ExpandCurrentTier

# [ function ] SlotFocusMission

# [ function ] onMouseWheel

# [ function ] IsTierExpanded

# [ function ] SearchArray

