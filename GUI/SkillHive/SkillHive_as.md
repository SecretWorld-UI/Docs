# [ file ] SkillHive.as

# [ group ] Variables

# [ variable ] TEMPLATE

# [ variable ] CELL

# [ variable ] WHEEL_PADDING

# [ variable ] INNER_RADIUS

# [ variable ] INNER_RADIUS_BACKGROUND

# [ variable ] PANE_HEADER_OFFSET

# [ variable ] PANE_CLOSE_WIDTH

# [ variable ] SCROLL_INTERVAL

# [ variable ] PANEL_TWEEN_SPEED

# [ variable ] ACTIVE_SHORTCUT_FIRST_SLOT

# [ variable ] PASSIVE_SHORTCUT_FIRST_SLOT

# [ variable ] AUGMENT_SHORTCUT_FIRST_SLOT

# [ variable ] DAMAGE_AUGMENT

# [ variable ] SUPPORT_AUGMENT

# [ variable ] HEALING_AUGMENT

# [ variable ] SURVIVABILITY_AUGMENT

# [ variable ] DAMAGE_AUGMENT_BIT

# [ variable ] HEALING_AUGMENT_BIT

# [ variable ] SURVIVABILITY_AUGMENT_BIT

# [ variable ] SUPPORT_AUGMENT_BIT

# [ variable ] AUXILLIARY_SLOT_ACHIEVEMENT

# [ variable ] AUGMENT_SLOT_ACHIEVEMENT

# [ variable ] ULTIMATE_ABILITY_UNLOCK

# [ variable ] m_SelectedAbilityWheel

# [ variable ] m_SelectedAbilityWheelIndex

# [ variable ] m_AbilityWheels

# [ variable ] m_AbilityWheelButtons

# [ variable ] m_AbilityWheelSelector

# [ variable ] m_UpdateOnAdvancedChanged

# [ variable ] m_RingBackground

# [ variable ] m_TemplateFilter

# [ variable ] m_IsWidescreen

# [ variable ] m_Character

# [ variable ] m_ActiveDialog

# [ variable ] m_ShowTemplateAbilities

# [ variable ] m_DeselectAbilityClip

# [ variable ] m_IsDraggingAbility

# [ variable ] m_TrainedAbilities

# [ variable ] m_CellAbilities

# [ variable ] m_CellAbilitiesHeight

# [ variable ] m_DefaultCellAbilityHeight

# [ variable ] m_SelectedCellPowers

# [ variable ] m_SelectedCellAbilityClip

# [ variable ] m_CurrentEquipPanel

# [ variable ] m_CurrentEquipPopupHolder

# [ variable ] m_CurrentEquipPopupMenu

# [ variable ] m_SelectedFeat

# [ variable ] m_DetailedText

# [ variable ] m_UltimateTooltip

# [ variable ] m_PanelScale

# [ variable ] i_Cell

# [ variable ] m_VisibleSheet

# [ variable ] m_DefaultSkillhiveBackgroundWidth

# [ variable ] m_SelectedTemplate

# [ variable ] m_TemplateFilterArray

# [ variable ] m_SidePanesArray

# [ variable ] m_PaneLayoutArray

# [ variable ] m_Mask

# [ variable ] m_PanelOpenWidths

# [ variable ] m_x

# [ variable ] m_Y

# [ variable ] m_NumOpen

# [ variable ] m_IsPowerInventoryOpen

# [ variable ] m_PassiveBarVisible

# [ variable ] m_ActiveBarVisible

# [ variable ] m_CharacterSkillPointGUIMonitor

# [ variable ] m_ResourceIconMonitor

# [ variable ] m_AdvancedTooltipMonitor

# [ variable ] m_ShowAdvancedTooltips

# [ variable ] m_HyperLinkClicked

# [ variable ] m_LastClickedCellAbility

# [ variable ] m_PowerInventory

# [ variable ] m_AugmentWheelIndex

# [ variable ] m_MainWheelIndex

# [ variable ] m_AuxilliaryWheelIndex

# [ variable ] m_AbilityClipNameHeight

# [ variable ] m_AbilityClipTypeY

# [ variable ] m_AbilityClipDescriptionY

# [ variable ] m_AbilityClipDescriptionHeight

# [ variable ] m_AbilityClipAugmentLevelY

# [ group ] Functions

# [ function ] onLoad

# [ function ] drawCellSidePanel

# [ function ] SwitchToAugment

# [ function ] SwitchToAuxilliary

# [ function ] SlotAbilityWheelButton

# [ function ] SlotNextAbilityWheel

# [ function ] SlotPreviousAbilityWheel

# [ function ] ToggleNoCellSelectedMessage

# [ function ] SetSelectedAbilityWheel

# [ function ] ToggleAbilityWheelButtonsSizes

# [ function ] UpdateAbilityWheelVisibility

# [ function ] ShowAbilityWheels

# [ function ] CreateMainSkillWheel

# [ function ] CreateAuxilliaryWheel

# [ function ] CreateAugmentWheel

# [ function ] GetAbilityWheelContainingCluster

# [ function ] onUnload

# [ function ] CloseSkillHive

# [ function ] SlotSkillHiveHelp

# [ function ] OnModuleDeactivated

# [ function ] OnModuleActivated

# [ function ] ResizeHandler

LAYOUT FUNCTIONALITY

---

# [ function ] SetAspectRatio

# [ function ] Layout

# [ function ] GetLeftSideWidth

the sidepanes

---

# [ function ] SlotDragHandled

# [ function ] SlotCellSelected

# [ function ] SlotCellAbilitySelected

# [ function ] SlotWheelAnimated

# [ function ] SlotAbilitySelected

# [ function ] RefreshSkillWheel

Refreshes and redraws the entire skillwheel

---

# [ function ] SlotFeatUntrained

# [ function ] SlotFeatTrained

# [ function ] ShowPassiveBar

PASSIVE / ACTIVE BAR FUNCTIONALITY

---

# [ function ] ShowActiveBar

# [ function ] SlotDragBegin

# [ function ] SlotToggleVisibilityPassiveBar

# [ function ] SlotToggleVisibilityActiveBar

# [ function ] CreateScrollbar

SCROLLBAR FUNCTIONALITY

---

# [ function ] UpdateScrollBar

# [ function ] RemoveScrollBar

# [ function ] onMouseWheel

# [ function ] OnCellScrollbarUpdate

when interacting with the scrollbar

---

# [ function ] SlotCellAbilityPress

update the position of the abilities

---

# [ function ] SlotCellMouseDown

# [ function ] SlotCellMouseUp

# [ function ] SlotHyperLinkClicked

# [ function ] CellAbilityPress

# [ function ] SlotCellAbilityRelease

# [ function ] SlotAbilityTextRelease

# [ function ] CellAbilityRelease

# [ function ] EquipAbilityInFirstFreeSlot

# [ function ] SlotUpdateCellPanelTimer

# [ function ] SlotUpdateCellPanel

# [ function ] SelectCellAbility

Called when an ability has been selected. This function will expand/close / the selected ability, and interpolate the other abilities /@param abilityIdx [in] the index of the ability pressed in the cell ( 0 -> NumAbilities) /@param toggle [in] will deselect an ability if it is already open

---

# [ function ] InterpolateAbilities

Interpolates/tweens all abilities to the correct position

---

# [ function ] SelectAbility

# [ function ] DeselectAbility

tween the selected line around

---

# [ function ] CreateDetailedTextClip

# [ function ] SlotBuyAbility

FUNCTIONALITY FOR ABILITY BUTTONS

---

# [ function ] BuyAbility

# [ function ] TrainFeat

# [ function ] RefundAbility

# [ function ] SlotRefundAbility

# [ function ] UnEquipAbility

# [ function ] EquipAbility

# [ function ] SlotEquipButtonRollOver

# [ function ] SlotEquipButtonRollOut

# [ function ] SlotEquipButtonPressed

# [ function ] RemoveEquipPopup

# [ function ] SlotRemoveEquipPopup

# [ function ] FillAbilityClips

# [ function ] UpdateAbilityClips

# [ function ] SetupCellAbility

# [ function ] UpdateUltimateAbility

# [ function ] ShowUltimateTooltip

# [ function ] CloseUltimateTooltip

# [ function ] FloatUltimateTooltip

# [ function ] SlotNextUltimateAbility

# [ function ] SlotPreviousUltimateAbility

# [ function ] UpdateAbilityCostButton

# [ function ] SetupPowerInventory

# [ function ] PowerInventoryClickHandler

# [ function ] UpdatePowerInventoryPosition

# [ function ] SetupSkillPointsPanel

# [ function ] SlotUpdateAdvancedTooltips

# [ function ] ToggleAdvancedTooltips

# [ function ] UpdateResourceIcons

# [ function ] SlotToggleCharacterSkillPointGUI

# [ function ] CharacterSkillPointButtonHandler

# [ function ] AnimateCharacterSkillPointPanel

# [ function ] GetSidepaneWidth

# [ function ] SetupSidePanes

LAYOUT OF THE TABS (the part you interact with at least) mc: i_Tab // the tab i_ExpandableTab     // the bit with the name sideways i_TabClip       // tha actual clip that gets moved in and out i_Text      // the vertical textfield i_TabArrow  // the arrows used to open the pane (the open method is actually triggered on i_TabClip) i_Text              // the horizontal textfield i_TabArrow          // the arrows you click to collapse the pane

Sets up the sidepanes positions in their default setup ( do we need to change this to support saved state?)

---

# [ function ] OpenPane

Opens a pane

## Parameters

<pre>
<em>param</em> |    obj:Object - object containing reference to the pane we open
<em>param</em> |    x:Number - the new xpos                                     
</pre>

---

# [ function ] MovePane

If a pane kkeps its old state, but chenges position because other panes move.

## Parameters

<pre>
<em>param</em> |    obj:Object - the object that wraps the pane
<em>param</em> |    x:Number - the position to tween to        
</pre>

---

# [ function ] ClosePane

Closes a pane

## Parameters

<pre>
<em>param</em> |    obj:Object - object containing reference to the pane we close
<em>param</em> |    x:Number - the new xpos                                      
</pre>

---

# [ function ] ShowClip

tweens a clip in, makes sure it is at 0 alpha and visible first

## Parameters

<pre>
<em>param</em> |    clip:MovieClip - the clip to hide                                                      
<em>snap</em>  | :Boolean - flag indication if we are just moving the tab, thus not tweening the openstate 
</pre>

---

# [ function ] HideClip

Hides a clip by tweening out and then hiding

## Parameters

<pre>
<em>param</em> |    clip:MovieClip - the button to hide                                                    
<em>snap</em>  | :Boolean - flag indication if we are just moving the tab, thus not tweening the openstate 
</pre>

---

# [ function ] SlotSwitchSheet

switches sheet on demend

---

# [ function ] UpdateBackgroundAndBarPositions

check towards old positions and execute

---

# [ function ] SetSidePaneMask

# [ function ] UpdateTotalSkillpoints

# [ function ] UpdateHiveCompletion

# [ function ] SlotTokenChanged

# [ function ] SlotUpdateShortcuts

# [ function ] IsFeatInTemplate

TEMPLATE FUNCTIONALITY*

---

# [ function ] GetTemplateClipName

# [ function ] SlotToggleTemplateAbilities

# [ function ] SlotTemplateSelected

# [ function ] ShowTemplates

# [ function ] RGB

HELPER FUNCTIONS

---

# [ function ] IsPaneOpen

# [ function ] IsPaneLocked

# [ function ] GetCellAbilityClip

# [ function ] IsPassiveAbility

# [ function ] IsActiveAbility

# [ function ] GetPowerLevelColor

