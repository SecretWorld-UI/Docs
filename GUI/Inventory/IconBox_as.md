# [ class ] GUI.Inventory.IconBox

# [ group ] Variables

# [ variable ] EXPAND_ITEM_BUTTON_SPACE

# [ variable ] BOTTOM_BAR_HEIGHT

# [ variable ] VISIBILITY_OFF

# [ variable ] VISIBILITY_ON

# [ variable ] VISIBILITY_PARTIAL

# [ variable ] WINDOW_CORNER_RADIUS

# [ variable ] m_Visible

# [ variable ] m_WindowMC

# [ variable ] m_Grid

# [ variable ] m_BottomBar

# [ variable ] m_BoxID

# [ variable ] m_IconSize

# [ variable ] m_IconPaddingX

# [ variable ] m_IconPaddingY

# [ variable ] m_BoxPadding

# [ variable ] m_BottomBarHeight

# [ variable ] m_TopBarHeight

# [ variable ] m_CanRename

# [ variable ] m_BoxHeight

# [ variable ] m_BoxWidth

# [ variable ] m_NumRows

# [ variable ] m_NumColumns

# [ variable ] m_NumItems

# [ variable ] m_MinNumRows

# [ variable ] m_MinNumColumns

# [ variable ] m_Name

# [ variable ] m_IsPinned

# [ variable ] m_IsGlowing

# [ variable ] m_HasGrid

# [ variable ] m_HasBottomBar

# [ variable ] m_WindowHasFullVisibility

# [ variable ] m_PinnedBackgroundOpacity

# [ variable ] m_LockPositionWhenPinned

# [ variable ] m_ItemSlots

# [ variable ] m_InventoryId

# [ variable ] SignalStartDragging

# [ variable ] SignalDeleteItem

# [ variable ] SignalUseItem

# [ variable ] SignalStartDragItem

# [ variable ] SignalStartSplitItem

# [ variable ] SignalMouseDownItem

# [ variable ] SignalMouseUpItem

# [ variable ] SignalMouseUpEmptySlot

# [ variable ] SignalMouseDownEmptySlot

# [ group ] Functions

# [ function ] IconBox

# [ function ] SlotBackgroundPressed

# [ function ] SlotBackgroundReleased

# [ function ] SlotMouseDownEmptySlot

# [ function ] SlotMouseUpEmptySlot

# [ function ] SlotStartDrag

# [ function ] SlotTopPressed

# [ function ] SlotMouseOverButton

# [ function ] SlotMouseOutButton

# [ function ] CloseAllTooltips

# [ function ] SlotPinPress

# [ function ] GetWindowMC

# [ function ] GetNumItems

# [ function ] GetName

# [ function ] SetName

# [ function ] SetNumTotalItems

# [ function ] IsPinned

# [ function ] SetPinned

# [ function ] IsGlowing

# [ function ] SetGlowing

# [ function ] IsVisible

# [ function ] GetNumColumns

# [ function ] GetNumRows

# [ function ] GetNumSlots

# [ function ] CalculateSlotPosX

# [ function ] CalculateSlotPosY

# [ function ] RelayoutSlots

# [ function ] GetGridPositionAt

# [ function ] GetFirstFreeGridPosition

# [ function ] GetItemAtGridPosition

# [ function ] IsValidGridPosition

# [ function ] GetItemAt

# [ function ] HitTest

# [ function ] HitTestTopBar

# [ function ] GetBoxID

# [ function ] GetWidth

# [ function ] GetHeight

# [ function ] SetPos

# [ function ] GetPos

# [ function ] GetHorizontalSizeOfSlots

# [ function ] GetVerticalSizeOfSlots

# [ function ] GetNumHorizontalSlotsFromSize

# [ function ] GetNumVerticalSlotsFromSize

# [ function ] UpdateBoxContents

# [ function ] UpdatePinnedBoxContents

writes the box only if the state is pinned and the inventory is hidden. The box is only the frame around the icons

## Parameters

<pre>
<em>width</em>  | :Number - witdh of the box to draw 
<em>height</em> | :Number - height of the box to draw
</pre>

## Returns

Void

---

# [ function ] UpdateDropShadow

# [ function ] SetOnScreenVisibility

# [ function ] UpdateVisibility

# [ function ] SetWindowHasFullVisibility

# [ function ] RemoveItem

# [ function ] ChangeItem

# [ function ] AddShortcutLabelAndAnimation

# [ function ] RemoveShortcutLabelAndAnimation

# [ function ] GetMovieClipFromInventoryPosition

# [ function ] GetGridPositionFromSlotID

# [ function ] AnimateShortcut

# [ function ] ResizeBox

# [ function ] ResizeBoxTo

# [ function ] UpdateItemSlotsArray

# [ function ] GetHighestSlotUsed

# [ function ] CreateEmptySlot

# [ function ] DrawGrid

# [ function ] RemoveGrid

# [ function ] HasGrid

# [ function ] RedrawGrid

# [ function ] CanRename

# [ function ] SlotRenameBox

when clicking the title of the inventory, the rename variable is set to true for a second if a user clicks again while the rename variable is true, it will enable them to edit the text

---

# [ function ] StartWritingName

# [ function ] SlotNameEnterFrame

# [ function ] SlotMouseDownEndWritingName

# [ function ] EndWritingName

# [ function ] onKeyDown

# [ function ] GetInventoryID

# [ function ] GetIconSize

# [ function ] GetIconPaddingX

# [ function ] GetIconPadingY

# [ function ] GetBoxPadding

# [ function ] GetTopBarHeight

# [ function ] GetBottomBarHeight

# [ function ] SetHasBottomBar

# [ function ] GetHasBottomBar

# [ function ] SetPinnedBackgroundOpacity

# [ function ] SetLockPositionWhenPinned

