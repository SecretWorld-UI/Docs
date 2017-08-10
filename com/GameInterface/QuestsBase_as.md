# [ class ] com.GameInterface.QuestsBase

## Important concepts

Tier == MainQuest in GC == Quest in the quest tool. Task == Quest in GC     == Task in the quest tool. Goal == QuestGoal in GC == Goal in the quest tool.

A Mission consist of several Tiers linked together. One Tier consist of one or many Tasks and each Task consist of one or many Goals. You can not see the list of Tasks, only the CurrentTask.

---

# [ group ] Functions

# [ function ] DeleteCurrentQuestOfMainQuest

Delete a tier.

## Parameters

<pre>
<em>tier</em> | :Number  The tier to delete.
</pre>

---

# [ function ] AcceptQuestFromQuestgiver

Tell the questgiver that you would like to start the quest in question. If you got the quest, you should also get a "QuestAdded" signal.

## Parameters

<pre>
<em>idQuestGiver</em>       | :Number        The quest in question.         
<em>questGiverType</em>     | :Number      The type of the questgiver dynel.
<em>questGiverInstance</em> | :Number  The instance of the questgiver dynel.
</pre>

---

# [ function ] GetQuest

Request infop about this quest

---

# [ function ] GetQuestGiver

# [ function ] GetQuestByQuestGiverID

# [ function ] GetAllAbandonedQuests

This will get an array containing the current missions.

---

# [ function ] GetMainQuestIDByQuestID

Returns the ID of the main quest for the quest identified by @a questID, or quests::INVALID_MAINQUEST_ID on error.

---

# [ function ] GetMainQuestLevel

Returns the level restriction of the main quest

---

# [ function ] GetAllActiveQuests

This will get an array containing the current missions.

---

# [ function ] GetAllCompletedQuests

This will get an array of all completed missions.

---

# [ function ] GetAllCompletedQuestsByRegion

This will get an object containing arrays of completed missions per playfield.

---

# [ function ] GetAllQuestsOnCooldown

This will get an array of all missions on cooldown

---

# [ function ] GetAllActiveChallenges

# [ function ] GetAllCompletedChallenges

# [ function ] IsMissionActive

Return true if a mission is active.

---

# [ function ] IsMissionPaused

Return true if a mission is paused.

---

# [ function ] IsChallengeMission

Return true if a mission is a challenge.

---

# [ function ] ShareQuest

# [ function ] ShareQuestUnderMouse

# [ function ] PauseQuest

# [ function ] ShowQuestOnMap

# [ function ] AcceptQuestReward

# [ function ] IsSwitchNecessary

# [ function ] ShowMedia

# [ function ] CloseMedia

# [ function ] ShowQuestTaskMedia

# [ function ] GetSolvedTextForQuest

# [ function ] MissionReportWindowOpened

# [ function ] GetAllRewards

Get all uncollected quest rewards.

## Returns

Array of objects with m_QuestTaskID:Number, m_Rewards:Array, m_OptionalRewards:Array

---

# [ function ] GetAllChallengeRewards

Get all uncollected challenge rewards.

## Returns

Array of objects with m_QuestTaskID:Number, m_Rewards:Array, m_OptionalRewards:Array

---

# [ function ] AnyUnsentReports

Returns true or false depening if there are any unsubmitted reports with rewards pending

## Returns

Boolean: Are there quests with reward pending

---

# [ group ] Variables

# [ variable ] SignalQuestAvailable

You get this signal when someone has requested seeing the list of available quests for a given object. This could be triggered by the actionscript or by gamecode. You get 1 signal per available quest from this questGiverType/questGiverInstance.

## Parameters

<pre>
<em>idQuestGiver</em>       | :Number        The quest giver id. Points at exactly 1 quest.                      
<em>questName</em>          | :String           The name of the quest.                                           
<em>mainQuestType</em>      | :Number       The type of quest. (TODO: figure out the types? Changes in the plan.)
<em>unused</em>             | :Number              Unused.                                                       
<em>questGiverType</em>     | :Number      The type of the questgiver dynel.                                     
<em>questGiverInstance</em> | :Number  The instance of the questgiver dynel.                                     
<em>tier</em>               | :Number                The quest tier.                                             
</pre>

---

# [ variable ] SignalGoalProgress

You get this signal when something causes the given quest to progress. This is triggered by gamecode for instance when you kill a monster or pick up an item in the form of having complete 4 of 10. Note that if a goals SolvedTimes == RepeatCount, then the goal is done.

## Parameters

<pre>
<em>tierId</em>      | :Number        The id of the main quest.            
<em>goalId</em>      | :Number        The id of the goal.                  
<em>solvedTimes</em> | :Number   The new solved count.                     
<em>repeatCount</em> | :Number   The number of times to repeate until done.
</pre>

---

# [ variable ] SignalGoalPhaseUpdated

You get this signal when something causes the given quest to update its phase

## Parameters

<pre>
<em>tierId</em> | :Number        The id of the main quest.
</pre>

---

# [ variable ] SignalGoalFinished

You get this signal when a goal is completed. This is triggered by gamecode for instance when you kill a monster or pick up an item in the form of having complete 4 of 10.

## Parameters

<pre>
<em>tierId</em> | :Number        The id of the tier.
<em>goalId</em> | :Number        The id of the goal.
</pre>

---

# [ variable ] SignalQuestEvent

Different events sent from Task. e_QuestEvent_Expired,    - A task expired. e_QuestEvent_Completed,  - A task was completed. e_QuestEvent_Failed,     - A task failed. e_QuestEvent_Removed,    - When you get this, the playertiers list is already updated. e_QuestEvent_RewardChanged, e_QuestEvent_UntrainCraft

---

# [ variable ] SignalTaskAdded

This is called when you get a new task. So it would be called when you just got a new tier, and when a task is completed and there exist more tasks for the given tier. The task number is not important as we only operate with current task.

## Parameters

<pre>
<em>tierId</em> | :Number        The id of the tier.
</pre>

---

# [ variable ] SignalMissionRemoved

You get this signal when a tier is removed from the list. Note that this does not say anything about the tier being completed or failed. That info does not seem to exist. Checking the last questevent status might give a clue.

## Parameters

<pre>
<em>tierId</em> | :Number        The id of the main quest.
</pre>

---

# [ variable ] SignalPlayerTiersChanged

TODO: Document the rest

---

# [ variable ] SignalQuestChanged

# [ variable ] SignalTierCompleted

Fired when you complete a tier. TierRemoved will be sent afterwards.

## Parameters

<pre>
<em>tier</em> | :Number        The id of the tier.
</pre>

---

# [ variable ] SignalTierFailed

Fired when you've failed a tier. TierRemoved will be sent afterwards.

## Parameters

<pre>
<em>tier</em> | :Number        The id of the tier.
</pre>

---

# [ variable ] SignalMissionCompleted

Fired when you complete a mission.

## Parameters

<pre>
<em>missionid</em> | :Number        The id of the mission.
</pre>

---

# [ variable ] SignalMissionFailed

Fired when you've failed a tier. TierRemoved will be sent afterwards.

## Parameters

<pre>
<em>tier</em> | :Number        The id of the mission.
</pre>

---

# [ variable ] SignalCompletedQuestsChanged

Fired when you've failed a tier. TierRemoved will be sent afterwards.

## Parameters

<pre>
<em>tier</em> | :Number        The id of the mission.
</pre>

---

# [ variable ] SignalQuestCooldownChanged

Fired when a quest cooldown changes.

## Parameters

<pre>
<em>tier</em> | :Number
<em>tier</em> | :Number
</pre>

---

# [ variable ] SignalQuestGiverEnterVicinity

Triggered when you come within 30meter of a questgiver. Then use this info to call RequestAvailableQuests to see if it has any quests for you. Note that the c++ ASQuest class must have been setup correctly to use this feature.

## Parameters

<pre>
<em>type</em>     | :Number      The type of the quest giver.
<em>instance</em> | :Number  The instance of the quest giver.
</pre>

---

# [ variable ] SignalQuestGiverLeaveVicinity

Triggered when a questgiver leaves your 30m vicinity. Either caused by distance, death, or playfield shift.

## Parameters

<pre>
<em>type</em>     | :Number      The type of the quest giver.
<em>instance</em> | :Number  The instance of the quest giver.
</pre>

---

# [ variable ] SignalGoalTimeLimitChanged

Triggered when a goal updates its timelimit

## Parameters

<pre>
<em>goalID</em> | :Number The goal template id
</pre>

---

# [ variable ] SignalQuestRewardMakeChoice

Triggered when there is a quest reward to choose.

---

# [ variable ] SignalQuestRewardInventorySpace

# [ variable ] SignalQuestRewardAcceptAcknowledged

# [ variable ] SignalSendMissionReport

Triggered when player hits key combo to open the quest reward window(s)

---

# [ variable ] SignalOpenMissionWindow

Triggered from gamecode when player uses an npc that has quests @param: ID32

---

