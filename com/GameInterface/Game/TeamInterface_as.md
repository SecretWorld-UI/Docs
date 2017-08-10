# [ class ] com.GameInterface.Game.TeamInterface

# [ group ] Functions

# [ function ] RequestTeamInformation

# [ function ] GetClientTeamInfo

# [ function ] GetClientRaidInfo

# [ function ] IsInTeam

Returns true if the dynel is in a team. Returns false if not in team or if the dynel is not on the client.

---

# [ function ] IsInRaid

Returns true if the dynel is in a raid. Returns false if not in team or if the dynel is not on the client.

---

# [ function ] CanSummonHere

Returns true if the team leader can summon other people to this playfield

---

# [ function ] InviteToTeam

Invite the id to join the players team.

---

# [ function ] PromoteToLeader

Promote the id to become leader of the players team.

---

# [ function ] KickFromTeam

Kick the id from the players team.

---

# [ function ] CanVoteKickFromTeam

Returns true if the client can start a vote kick

---

# [ function ] StartVoteKick

Initiates a vote to kick the given player

---

# [ function ] ToggleLootOptions

Open the loot options GUI

---

# [ function ] CanLeaveTeam

Check if you can leave a team

---

# [ function ] LeaveTeam

Leave team.

---

# [ function ] CanStartVoteRetreat

# [ function ] StartVoteRetreat

Vote to retreat

---

# [ function ] AcceptTeamInvite

Accept team invite from id.

---

# [ function ] SendJoinRequest

Accept team invite from id.

---

# [ function ] DeclineTeamInvite

Decline team invite from id.

---

# [ function ] AcceptRaidInvite

Accept raid invite from id.

---

# [ function ] DeclineRaidInvite

Decline raid invite from id.

---

# [ function ] CreateRaid

# [ function ] LeaveRaid

# [ function ] InviteToRaid

# [ function ] CanRaidMoveSelf

# [ function ] MarkForTeamMove

# [ function ] GetCharacterMarkedForTeamMove

# [ function ] CancelTeamMove

# [ function ] TeamSwap

# [ function ] TeamMove

# [ function ] KickFromRaid

# [ function ] SummonRequest

# [ function ] SendTeamSwapRequest

# [ function ] IsClientTeamLeader

# [ function ] IsTeamLeader

# [ function ] IsClientRaidLeader

# [ function ] IsInClientTeam

# [ function ] IsInClientRaid

# [ function ] GetClientRaidID

# [ function ] GetClientTeamID

# [ function ] GetTeamIDFromRaid

# [ group ] Variables

# [ variable ] SignalTeamInvite

# [ variable ] SignalPromptJoinRequest

# [ variable ] SignalTeamInviteTimedOut

# [ variable ] SignalRaidInvite

# [ variable ] SignalRaidInviteTimedOut

# [ variable ] SignalClientJoinedTeam

# [ variable ] SignalClientLeftTeam

# [ variable ] SignalClientJoinedRaid

# [ variable ] SignalClientLeftRaid

# [ variable ] SignalMarkForTeamMove

# [ variable ] SignalUnmarkForTeamMove

# [ variable ] SignalShowVoteKickReasonPrompt

