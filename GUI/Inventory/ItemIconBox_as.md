# [ class ] GUI.Inventory.ItemIconBox

# [ group ] Variables

# [ variable ] m_IsDefaultBox

# [ variable ] m_IsResizing

# [ variable ] m_IsResizable

# [ variable ] m_IsScrollbarEnabled

# [ variable ] m_MaxItems

# [ variable ] m_SearchBox

# [ variable ] m_CurrentDialog

# [ variable ] SignalNewButtonPressed

# [ variable ] SignalCloseButtonPressed

# [ variable ] SignalTrashButtonPressed

# [ variable ] SignalSearch

# [ variable ] SignalBuySlots

# [ variable ] SignalMerge

# [ variable ] SignalStackItems

# [ group ] Functions

# [ function ] ItemIconBox

# [ function ] UpdateBuySlotsButton

# [ function ] SetNumTotalItems

# [ function ] SlotSearchText

# [ function ] SlotCloseButtonPressed

# [ function ] SlotBuySlots

# [ function ] SlotBuySlotsAnswer

# [ function ] UpdateBoxContents

# [ function ] SetWindowHasFullVisibility

# [ function ] ResizeBoxTo

# [ function ] SlotResizePress

# [ function ] SlotResizeRelease

# [ function ] SlotResizeMove

# [ function ] SlotHelpButtonPressed

# [ function ] SlotNewPress

# [ function ] SlotTrashPress

# [ function ] AddItemAtGridPosition

# [ function ] RemoveItem

# [ function ] ClearItem

# [ function ] CreateSlot

# [ function ] CreateEmptySlot

if no space, add the item invisible;

---

# [ function ] CreateScrollbar

TODO implement a scrollbar when content overflows the space. Today content is truncated to be invisible, but it is there when you resize the inventory

---

# [ function ] SlotDeleteItem

# [ function ] SlotMouseDownItem

# [ function ] SlotMouseUpItem

# [ function ] SlotStartDragItem

# [ function ] SlotStartSplitItem

# [ function ] AddItemAt

# [ function ] AddItem

# [ function ] AddItemToExistingSlot

# [ function ] MergeInto

# [ function ] GetItemSlot

# [ function ] GetItemData

# [ function ] GetSlotBindings

# [ function ] CloseAllTooltips

Closes all the tooltips if box is removed or enter a state where ist is invisible

---

# [ function ] UpdateFilteredItems

# [ function ] SetCooldown

# [ function ] RemoveCooldown

# [ function ] SetResizable

# [ function ] SortBag

# [ function ] SortByRarity

