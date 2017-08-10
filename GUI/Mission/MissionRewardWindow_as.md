# [ class ] GUI.Mission.MissionRewardWindow

# [ group ] Variables

# [ variable ] m_Height

# [ variable ] m_Width

# [ variable ] SignalClose

# [ variable ] m_Character

# [ variable ] m_Faction

# [ variable ] m_Inventory

# [ variable ] m_Mission

# [ variable ] m_ContentY

# [ variable ] m_RewardSize

# [ variable ] m_QuestID

# [ variable ] m_MainQuestID

# [ variable ] m_InnerPadding

# [ variable ] m_DescriptionBackground

# [ variable ] m_RewardBackground

# [ variable ] m_RewardArray

# [ variable ] m_OptionalRewardArray

# [ variable ] m_OptionalSelectedIcon

# [ variable ] m_Notifier

# [ variable ] m_XPReward

# [ variable ] m_CashReward

# [ variable ] m_CollectButton

# [ variable ] m_FactionLogo

# [ variable ] m_From

# [ variable ] m_To

# [ variable ] m_Subject

# [ variable ] m_FromText

# [ variable ] m_ToText

# [ variable ] m_SubjectText

# [ variable ] m_MissionDescription

# [ variable ] m_RewardHeader

# [ variable ] m_OptionalRewardHeader

# [ variable ] m_RewardDivider

# [ variable ] m_MemberBonusHeader

# [ variable ] m_BonusXPReward

# [ variable ] m_BonusCashReward

# [ variable ] m_MemberIcon

# [ variable ] m_InvisibleShopButton

# [ group ] Functions

# [ function ] MissionRewardWindow

# [ function ] configUI

# [ function ] SetData

# [ function ] AddRewards

# [ function ] Layout

repositions after a resize

---

# [ function ] SlotMemberStatusUpdated

iterate the Optional rewards

---

# [ function ] GetSize

# [ function ] SetSize

# [ function ] OptionalRewardsClickHandler

# [ function ] GetFactionLogo

# [ function ] GetMissionObject

returns the Mission object from the taskl id of this mission

## Parameters

<pre>
<em>id</em> | :Number - the currenttask id
</pre>

## Returns

quests - or null if there is no quest with this id

---

# [ function ] CollectRewardsHandler

# [ function ] ShopButtonReleaseHandler

# [ function ] Close

# [ function ] GetID

