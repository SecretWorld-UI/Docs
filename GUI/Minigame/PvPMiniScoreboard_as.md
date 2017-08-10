# [ file ] PvPMiniScoreboard.as

# [ group ] Variables

# [ variable ] m_TimerPanel

# [ variable ] m_TokenPanel

# [ variable ] m_FlagPanel

# [ variable ] SIDE_SCORE

# [ variable ] SIDE_FLAGS

# [ variable ] PLAYER_CAPTURED_FLAG

# [ variable ] PLAYER_RETURNED_FLAG

# [ variable ] PANEL_STATE_NORMAL

# [ variable ] PANEL_STATE_DOMINATION

# [ variable ] m_PanelState

# [ variable ] EL_DORADO_ID

# [ variable ] SHAMBALA_ID

# [ variable ] STONEHENGE_ID

# [ variable ] m_TokenSize

# [ variable ] m_MaxFlags

# [ variable ] m_PlayerMaxFlags

# [ variable ] m_UpdateTimer

# [ variable ] m_DominationTime

domination, who got all flags

---

# [ variable ] m_DominationTimeStarted

# [ variable ] m_DominationTimerId

# [ variable ] m_DominationTimeRefreshSpeed

# [ variable ] m_DominationSide

# [ variable ] m_TokenLinkage

# [ variable ] m_TokenName

# [ variable ] m_UseDropFlags

# [ variable ] m_DisabledAlpha

# [ variable ] m_UnfocusedAlpha

# [ variable ] m_TDB_Overtime

# [ variable ] m_TDB_Timeleft

# [ variable ] m_TDB_TimeToStart

# [ variable ] m_FilterArray

# [ variable ] m_Sides

# [ variable ] m_Character

# [ variable ] m_PlantFlagEnabled

# [ variable ] m_MissionTierInfoDValue

the d value for the missiontierinfo

---

# [ variable ] m_PVPMiniScoreDValue

# [ variable ] m_PvPNotifierDValue

# [ variable ] m_EditModeMask

# [ group ] Functions

# [ function ] onLoad

# [ function ] GetName

create the glow filter we'll use later

---

# [ function ] OnUnload

the method called by SFClipLoader

---

# [ function ] UpdateVisibility

# [ function ] OnUpdateTimer

start the countdowm

---

# [ function ] SlotStatChanged

Listens to StatChanges on the character and passing on the stat to update in necessary

---

# [ function ] UpdateFlags

Updates the flags a character holds

---

# [ function ] GetMaxNumFlags

calculates and returns the max number of flags

## Returns

Number - the max number of flags 

---

# [ function ] UpdateTokens

Updates the flag tokens by resizing the bacground of the tokens, lay them out and highlight the dominant faction

## Parameters

<pre>
<em>param</em> |   side:Number - the side to update 
</pre>

---

# [ function ] SetPanelStateDomination

Updates the TokenPanel and TimerPanel, adding the leading team's color and, text and a timer

## Parameters

<pre>
<em>param</em> |   side:Number             - The faction enum and index of m_Sides array
<em>param</em> |   isDominating:Boolean    - Add or the remove the dominationframe      
</pre>

---

# [ function ] OnDominationTimerUpdate

# [ function ] InitLayout

Called to clear teh graphics scores and flags when initializing and hiding sets up the stage corresponding to the type of minigame

---

# [ function ] SlotPlantFlag

Remove player flags

---

# [ function ] SlotScoreChanged

Called when the PvPMinigame.SignalPvPMinigameScoreChanged signal is emitted. Iterates the sides and gets their score, if  a score has changed, write the new values

---

# [ function ] SlotMatchRemoved

# [ function ] SlotMatchStarted

# [ function ] SlotMatchEnded

# [ function ] SlotMinigameStartsInXSeconds

# [ function ] SlotMatchWantsToStart

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

