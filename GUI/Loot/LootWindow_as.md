# [ class ] GUI.Loot.LootWindow

# [ group ] Variables

# [ variable ] ASSIGN_LABEL

# [ variable ] ASSIGN_ITEM_TO

# [ variable ] RIGHT_CLICK_MOUSE_OFFSET

# [ variable ] m_Padding

# [ variable ] SignalLootWindowClosed

# [ variable ] m_Inventory

# [ variable ] m_ItemSlots

# [ variable ] m_LootBagMC

# [ variable ] m_LootbagBackground

# [ variable ] m_CloseButton

# [ variable ] m_RightClickMenu

# [ variable ] m_NumLootItemsPerLine

# [ variable ] m_LootbagPadding

# [ variable ] m_LootItemsPadding

# [ variable ] m_RightClickSelectedItemSlot

# [ variable ] m_CharactersToLoot

# [ variable ] m_MasterLooterConfirmDialog

# [ variable ] m_Client

# [ variable ] m_LootHelpText

# [ variable ] m_NumRows

# [ variable ] m_IconSize

# [ variable ] m_ID

# [ variable ] m_LootBag

# [ variable ] STATE_DRAGGING

# [ variable ] m_MaxDragX

# [ variable ] m_MinDragX

# [ variable ] m_MaxDragY

# [ variable ] m_MinDragY

# [ group ] Functions

# [ function ] LootWindow

# [ function ] GetCharactersToLoot

attach the loot help text, and ensure clickthrough

---

# [ function ] AddTeamCharacters

# [ function ] AddRow

# [ function ] SetInventory

# [ function ] CreateRightClickMenu

# [ function ] SlotHideRightClickMenu

# [ function ] UpdateRightClickMenuItems

# [ function ] SlotShareLoot

# [ function ] SlotConfirmShareLoot

# [ function ] GetNumItems

# [ function ] DrawBackground

# [ function ] StartDragLootBag

draw the background of the items now that all slots are done

---

# [ function ] HideRighClickMenu

# [ function ] PositionRightClickMenu

# [ function ] CheckPositionLimits

# [ function ] CorrectPostion

# [ function ] GetID

# [ function ] SetCenterPosition

# [ function ] AddItem

# [ function ] StopDragLootBag

# [ function ] DragPositionCheck

# [ function ] onMouseOverButton

# [ function ] onMouseOutButton

# [ function ] IsSlotPersonalLoot

# [ function ] SlotMouseDownItem

# [ function ] LootItem

# [ function ] SlotStartDragItem

# [ function ] SlotDragHandled

# [ function ] GetItemSlot

# [ function ] SlotItemRemoved

# [ function ] ClearSlots

# [ function ] SlotChanged

# [ function ] SlotClose

# [ function ] CloseLootbag

# [ function ] DisconnectTooltip

disconnects all the tooltips if box is removed or enter a state where ist is invisible

---

