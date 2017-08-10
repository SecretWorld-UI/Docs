# [ file ] AbilityBar.as

# [ group ] Variables

# [ variable ] m_GadgetSlot

this is all the logic applying to the AbilityBar

---

# [ variable ] m_DodgeBar

# [ variable ] m_PotionSlot

# [ variable ] m_DeathPenalty

# [ variable ] m_DeathOverlay

# [ variable ] m_SprintIcon

# [ variable ] m_MainBar

# [ variable ] m_ItemBG

# [ variable ] m_CombatIndicator

# [ variable ] m_LMB_Hotkey

# [ variable ] m_RMB_Hotkey

# [ variable ] m_DodgeAnim

# [ variable ] m_AbilitySlots

# [ variable ] m_ItemSlots

# [ variable ] m_AbilityBarVisible

# [ variable ] m_ShowHotkeys

# [ variable ] m_Character

# [ variable ] m_UsedShortcut

# [ variable ] m_Inventory

# [ variable ] STATE_WRONG_HEAPON

# [ variable ] STATE_OUT_OF_RANGE

# [ variable ] STATE_NO_RESOURCE

# [ variable ] STATE_CASTING

# [ variable ] STATE_CHANNELING

# [ variable ] STATE_COOLDOWN

# [ variable ] STATE_GLOBAL_COOLDOWN

# [ variable ] STATE_ACTIVE

# [ variable ] STATE_MAX_MOMENTUM

# [ variable ] PLAYER_MAX_ACTIVE_SPELLS

# [ variable ] PLAYER_START_SLOT_SPELLS

# [ variable ] PLAYER_START_SLOT_POCKET

# [ variable ] PLAYER_MAX_ITEM_SHORTCUTS

# [ variable ] SPRINT_BUFFS

# [ variable ] DEATH_PENALTY_BUFF

# [ variable ] m_BaseWidth

# [ variable ] m_BigWidth

# [ variable ] m_BaseHeight

# [ variable ] m_InitialY

# [ variable ] m_SpellTemplatesSwap

# [ variable ] m_DodgeBuffSpellID

# [ variable ] m_DodgeIntervalID

# [ variable ] m_DodgeStartTime

# [ variable ] m_DodgeDuration

# [ variable ] m_DeathPenaltyTooltip

# [ variable ] m_DeathPenaltyTooltipTimeout

# [ variable ] m_EditModeMask

# [ group ] Functions

# [ function ] onLoad

# [ function ] OnModuleActivated

Update Hotkey Labels

---

# [ function ] onUnload

# [ function ] SlotToggleCombat

# [ function ] CreateItemSlot

# [ function ] SlotInvisibleBuffAdded

# [ function ] SlotBuffRemoved

# [ function ] UpdateDeathPenalty

# [ function ] SlotCharacterDead

# [ function ] SlotCharacterAlive

# [ function ] UpdateDeathOverlay

# [ function ] UpdateSprint

# [ function ] SprintMouseUp

# [ function ] DeathPenaltyMouseDown

# [ function ] DeathPenaltyMouseUp

# [ function ] DeathPenaltyRollOver

# [ function ] DeathPenaltyRollOut

# [ function ] StartDeathPenaltyTooltipTimeout

# [ function ] StopDeathPenaltyTooltipTimeout

# [ function ] OpenDeathPenaltyTooltip

# [ function ] CloseDeathPenaltyTooltip

# [ function ] UpdateDodgeBar

# [ function ] SlotAbilityBarVisibilityChanged

# [ function ] SlotHotkeyChanged

# [ function ] SlotShortcutbarHotkeysVisibleChanged

# [ function ] SlotMouseUpItem

# [ function ] SlotStartDragItem

# [ function ] SlotMouseUpEmptySlot

# [ function ] SlotItemDroppedOnDesktop

# [ function ] SlotDragHandled

# [ function ] SlotSwapShortcut

# [ function ] SlotRestoreSwapBar

# [ function ] ShowHotkeyLabels

# [ function ] SlotSwapBar

# [ function ] UpdateSwappedBar

# [ function ] IsAbilityShortcut

# [ function ] IsItemShortcut

# [ function ] SwapAbilities

# [ function ] SlotShortcutAdded

Signal sent when a shortcut has been added. This also happens when you teleport to a new pf. Note that you might get an SignalShortcutEnabled right afterward if the shortcut is disabled. And SignalCooldownTime if it's in cooldown.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotShortcutRemoved

Signal sent when a shortcut has been removed. This will not be sent if the shortcut changes position, moved.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position the item was added to. This is used for refering to this item.
</pre>

---

# [ function ] SlotShortcutMoved

Signal sent when a shortcut has been move to some other spot. No add/remove signal will be triggered.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position the item was move from.
<em>toPos</em>   | :Number     The position the item was move to.
</pre>

---

# [ function ] SlotShortcutEnabled

Signal sent when a shortcut is enabled/disabled. Will also be send when you enter a new playfield.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Number   0=disable, 1=enabled     
</pre>

---

# [ function ] SlotShortcutRangeEnabled

Signal sent when a shortcut is enabled/disabled via range.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Boolean   Enabled/Disabled        
</pre>

---

# [ function ] SlotShortcutResourceEnabled

Signal sent when a shortcut is enabled/disabled via resource.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
<em>enabled</em> | :Boolean   Enabled/Disabled        
</pre>

---

# [ function ] SlotShortcutUsed

# [ function ] SlotShortcutAddedToQueue

# [ function ] SlotShortcutRemovedFromQueue

# [ function ] SlotShortcutsRefresh

Signal that triggers every time the player load the game or teleports or whatever, will call the SlotShortcutAdded for every shortcut item.

---

# [ function ] SlotShortcutStatChanged

Signal sent when a shortcut changed one of it's stats. Probably most usefull for stacksize changes.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.                   
<em>stat</em>    | :Number      The stat that changed. See Enums/Stats.as
<em>value</em>   | :Number     The new value for the stat.               
</pre>

---

# [ function ] SlotItemRemoved

# [ function ] SlotItemCooldown

# [ function ] SlotItemCooldownRemoved

# [ function ] SlotCooldownTime

# [ function ] SlotSignalShortcutMaxMomentumEnabled

Method invoked when a shortcut is enters its max momentum.

## Parameters

<pre>
<em>itemPos</em> | :Number   The position of the item.
</pre>

---

# [ function ] SlotSignalCommandStarted

# [ function ] SlotSignalCommandEnded

# [ function ] SlotSignalCommandAborted

# [ function ] GetAbilitySlot

# [ function ] onDragBegin

# [ function ] GetMouseSlotID

# [ function ] onDragEnd

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

