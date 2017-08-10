# [ class ] GUI.SkillHive.AbilityWheel

# [ group ] Variables

# [ variable ] m_Id

# [ variable ] m_Name

# [ variable ] m_ShortName

# [ variable ] m_Character

# [ variable ] m_ButtonName

# [ variable ] m_IsCurrentWheel

# [ variable ] SignalCellSelected

# [ variable ] SignalCellAbilitySelected

# [ variable ] m_IsInitialized

# [ variable ] m_Clusters

# [ variable ] m_StartClusterList

# [ variable ] m_ClusterLookup

# [ variable ] m_CellArray

# [ variable ] m_LeafClusterIdArray

# [ variable ] m_ParentClusterIdArray

# [ variable ] m_SelectedCellClip

# [ variable ] m_ClusterDistance

# [ variable ] m_WheelBackground

# [ variable ] m_TemplateFilter

# [ variable ] m_RingInnerRadius

# [ variable ] m_BackgroundInnerRadius

# [ variable ] m_DrawShadow

# [ variable ] m_HoveredCell

# [ variable ] m_CellTooltip

# [ variable ] m_ClusterTooltip

# [ variable ] m_HoveringTooltip

# [ variable ] m_DrawClusterTooltip

# [ variable ] m_NumAbilities

# [ variable ] m_TrainedAbilities

# [ variable ] m_TemplateFilterClips

# [ variable ] m_TemplateFilterArray

# [ variable ] DAMAGE_AUGMENT

# [ variable ] SUPPORT_AUGMENT

# [ variable ] HEALING_AUGMENT

# [ variable ] SURVIVABILITY_AUGMENT

# [ group ] Functions

# [ function ] AbilityWheel

# [ function ] InitializeWheel

# [ function ] SetId

Accessors

---

# [ function ] SetName

# [ function ] SetShortName

# [ function ] GetId

# [ function ] GetName

# [ function ] GetShortName

# [ function ] SetButtonName

# [ function ] GetButtonName

# [ function ] SetStartClusters

# [ function ] SetClusters

# [ function ] SetCharacter

# [ function ] SetClusterDistance

# [ function ] GetClusterDistance

# [ function ] SetDrawShadow

# [ function ] SetWheelRadius

# [ function ] SetTemplateFilterArray

# [ function ] SetWheelBackground

# [ function ] SetTemplateFilterClip

# [ function ] FindCell

# [ function ] FindCluster

# [ function ] HasCluster

# [ function ] GetCellClip

# [ function ] GetCompletionText

# [ function ] GetTotalCompletion

# [ function ] GetTotalAbilities

# [ function ] GetSelectedCell

# [ function ] GetSelectedCellClip

# [ function ] SetSelectedCellFromIndex

# [ function ] MakeCluster

DRAWING FUNCTIONALITY

---

# [ function ] Redraw

# [ function ] DrawBackground

# [ function ] DrawTemplates

# [ function ] ClearTemplateFilterClips

# [ function ] IsLeafCluster

# [ function ] IsParentCluster

# [ function ] DrawSectorLine

# [ function ] CalculatePointOnCircumference

# [ function ] DrawCellTemplate

# [ function ] DrawSector

# [ function ] GetAbilitiesInTemplate

Template Functionality

---

# [ function ] IsFeatInTemplate

# [ function ] SlotRollOverCluster

MOUSE EVENTS

---

# [ function ] SlotRollOutCluster

# [ function ] SlotClickCell

# [ function ] SlotRollOutCell

# [ function ] SlotRollOverCell

# [ function ] SlotCellPressed

# [ function ] DeselectCell

# [ function ] SelectCell

# [ function ] OpenCellTooltip

CELL/CLUSTER TOOLTIPS

---

# [ function ] CheckRemoveCellTooltip

# [ function ] RemoveCellTooltip

# [ function ] RemoveClusterTooltip

# [ function ] MakeClusterTooltip

# [ function ] MakeCellTooltip

# [ function ] onRollOverTooltip

# [ function ] onRollOutTooltip

# [ function ] onPressTooltip

# [ function ] SlotTooltipAbilityPressed

# [ function ] CalculateNumAbilities

COMPLETION/SKILLPOINTS

---

# [ function ] GetNumClusterAbilities

# [ function ] CalculateCompletion

# [ function ] CalculateCellCompletion

# [ function ] CalculateClusterCompletion

# [ function ] SetIsCurrentWheel

# [ function ] GetIsCurrentWheel

