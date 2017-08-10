# [ file ] Backpack2.as

# [ group ] Variables

# [ variable ] m_ModuleActivated

# [ variable ] STATE_NONE

# [ variable ] STATE_DRAGGING_WINDOW

# [ variable ] STATE_RESIZING_WINDOW

# [ variable ] STATE_WRITING_NAME

# [ variable ] DEFAULT_INVENTORY_WINDOW

# [ variable ] m_HighestBoxDepth

# [ variable ] m_DefaultInventoryBox

# [ variable ] m_IconBoxes

# [ variable ] m_NextBoxId

# [ variable ] m_ActiveBox

# [ variable ] m_GlowingMergeBox

# [ variable ] m_State

# [ variable ] m_MaxNumBoxes

# [ variable ] m_Inventory

# [ variable ] m_InventoryVisible

# [ variable ] m_ChangeVisibliltyMonitor

# [ variable ] m_ScaleMonitor

# [ variable ] m_PinnedWindowsOpacityMonitor

# [ variable ] m_LockPositionWhenPinnedMonitor

# [ variable ] m_RightClickVendorSale

# [ variable ] m_EnableRightClickVendorSale

# [ variable ] m_EscapeStackNode

# [ variable ] m_SlotToBoxBindings

# [ variable ] m_CurrentDialog

# [ variable ] m_SaveConfigTimer

# [ variable ] m_SelectedItems

# [ variable ] m_DraggedItems

# [ variable ] m_ItemsToDelete

# [ variable ] m_SplitItemPopup

# [ variable ] m_OpenShop

# [ variable ] m_IsTrading

# [ variable ] m_ForceCharacterSheet

# [ group ] Functions

# [ function ] onLoad

# [ function ] onUnload

# [ function ] SlotTradeStarted

# [ function ] SlotTradeCompleted

# [ function ] SlotCharacterStatChanged

# [ function ] CheckSaveConfig

# [ function ] SaveConfig

# [ function ] OnModuleDeactivated

# [ function ] CreateConfig

# [ function ] OnModuleActivated

# [ function ] Layout

# [ function ] SlotScaleChanged

# [ function ] SlotPinnedWindowsOpacityChanged

# [ function ] SlotLockPositionWhenPinnedChanged

# [ function ] SlotRightClickVendorSaleChanged

# [ function ] SlotCloseInventory

# [ function ] ClampIconBoxes

# [ function ] ClampPos

# [ function ] UpdateVisibility

# [ function ] SlotEscapePressed

# [ function ] UpdateTotalNumItems

# [ function ] UpdateSlotToBoxBindings

# [ function ] GetSlotBinding

# [ function ] SlotNewPressed

# [ function ] GetBoxCount

# [ function ] SlotTrashPressed

# [ function ] SlotDeleteBox

# [ function ] DragBox

# [ function ] SlotBuySlots

# [ function ] SlotSearch

# [ function ] ResetFilter

# [ function ] CreateBox

creates a new inventory box and defines wether or not to start writing a name in the box

## Parameters

<pre>
<em>numRows</em>      | :Number - number of rows in the inventory                             
<em>numColumns</em>   | :Number - number of columns in the inventory                          
<em>isDefaultBox</em> | :Boolean - if defaultbox, add an "add" button and do not start writing
<em>isNew</em>        | :Boolean - is it a new inventory, then generate a new name.           
</pre>

---

# [ function ] CreateNewBox

# [ function ] FindNewPosition

# [ function ] IsBoxAtPos

increment the position by 20 till we do not overlap any windows

---

# [ function ] RemoveBox

# [ function ] SlotUseItem

# [ function ] SlotDeleteItem

# [ function ] SlotDeleteItemDialog

# [ function ] SlotMouseDownItem

# [ function ] SlotMouseUpItem

# [ function ] CanSellItem

# [ function ] CanUseForUpgrade

# [ function ] SlotMouseUpEmptySlot

# [ function ] SlotMouseDownEmptySlot

# [ function ] ClearSelectedItems

# [ function ] SlotStartSplitItem

# [ function ] SlotAcceptSplitItem

# [ function ] CloseSplitItemPopup

# [ function ] SlotCancelSplitItem

# [ function ] SlotStartDragItem

# [ function ] SlotDragHandled

# [ function ] SlotItemDroppedOnDesktop

# [ function ] SlotDeleteItemsDialog

# [ group ] Variables

# [ variable ] currentBox

# [ variable ] iconBox

# [ group ] Functions

# [ function ] SlotDragBegin

# [ function ] SlotDragEnd

# [ function ] MoveItemsToBox

# [ function ] MoveItemToFirstFreeSlot

# [ function ] SplitItem

# [ function ] SplitItemToEmptySlot

# [ function ] MoveItem

# [ function ] GetIconBoxIndexAt

# [ function ] GetInventoryMaxItems

# [ function ] GetIconBoxContainingItemSlot

# [ function ] CalcNumItems

# [ function ] SlotItemAdded

# [ function ] SlotItemLoaded

# [ function ] SlotItemRemoved

# [ function ] SlotItemChanged

# [ function ] SlotItemCooldown

# [ function ] SlotItemCooldownRemoved

# [ function ] SlotItemStatChanged

# [ function ] SlotOpenShop

# [ function ] SlotCloseShop

# [ function ] IsDraggedItem

# [ function ] SlotStackItems

