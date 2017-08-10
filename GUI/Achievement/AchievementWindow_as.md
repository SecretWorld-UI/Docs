# [ class ] GUI.Achievement.AchievementWindow

# [ group ] Variables

# [ variable ] m_ResizeButton

# [ variable ] m_Background

# [ variable ] m_ButtonBar

# [ variable ] m_CloseButton

# [ variable ] m_HelpButton

# [ variable ] m_Divider

# [ variable ] m_MainProgress

# [ variable ] m_SearchBox

# [ variable ] m_TotalPoints

# [ variable ] ACHIEVEMENT

# [ variable ] LORE

# [ variable ] SEASONAL_ACHIEVEMENT

# [ variable ] TITLE

# [ variable ] TUTORIAL

# [ variable ] m_IsResizing

# [ variable ] m_ViewY

# [ variable ] m_MenuY

# [ variable ] m_ProgressY

# [ variable ] m_MenuAllowedHeight

# [ variable ] m_ViewAllowedHeight

# [ variable ] m_CurrentSizePos

# [ variable ] m_MenuWidth

# [ variable ] m_ViewWidth

# [ variable ] m_MinWindowWidth

# [ variable ] m_MinWindowHeight

# [ variable ] m_MenuScrollbarEnabled

# [ variable ] m_ViewScrollbarEnabled

# [ variable ] m_Padding

# [ variable ] m_ViewScrollbar

# [ variable ] m_ViewMask

# [ variable ] m_MenuScrollbar

# [ variable ] m_MenuMask

# [ variable ] m_AchievementProgress

# [ variable ] m_CurrentTreeRootNode

# [ variable ] m_CurrentSelectedNode

# [ variable ] m_LoreDataNode

# [ variable ] m_AchievementDataNode

# [ variable ] m_SeasonalAchievementDataNode

# [ variable ] m_TDB_Achievements

# [ variable ] m_TDB_SeasonalAchievements

# [ variable ] m_TDB_Lore

# [ variable ] m_CurrentTab

# [ variable ] m_CurrentView

# [ variable ] m_CurrentViewPanel

# [ variable ] m_PanelLinkage

# [ variable ] m_CurrentMenu

# [ variable ] SignalClose

# [ variable ] m_NodeFocus

# [ variable ] SignalTagRead

# [ variable ] m_TabButtonArray

# [ group ] Functions

# [ function ] onUnload

# [ function ] AchievementWindow

# [ function ] configUI

# [ function ] ResizeWindow

# [ function ] SetSize

# [ function ] GetSize

# [ function ] SlotSetNodeFocus

# [ function ] GetTabId

# [ function ] GetHeaderId

# [ function ] SetTabFocus

# [ function ] GetTabFocus

# [ function ] Layout

# [ function ] SetAchievementProgress

# [ function ] ScrollToSelected

# [ function ] InitTabs

# [ function ] SlotTagAdded

# [ function ] SlotStatChanged

# [ function ] TabSelected

# [ function ] CreateView

# [ function ] SlotNodeClicked

remove the old and create a new view

---

# [ function ] SlotNodeSelected

# [ function ] UpdateMenuScrollBar

# [ function ] UpdateViewScrollBar

# [ function ] ScrollBar

# [ function ] onMouseWheel

listrens for scrollwheel and updates the correct area

---

# [ function ] OnScrollbarUpdate

# [ function ] UpdateAchievementProgressView

# [ function ] UpdateTotalAchievementPoints

# [ function ] UpdateProgressView

updates the progressbar for all views that use it

---

# [ function ] CreateDataNode

Returns a LoreNode obejct, but this is cached, so only retrieves when its not there or being forced

---

# [ function ] RemoveFocus

# [ function ] SlotCloseWindow

# [ function ] HelpButtonClickedEventHandler

# [ function ] SlotResizePress

# [ function ] SlotResizeRelease

# [ function ] SlotResizeMove

# [ function ] StartDragAchievementWindow

# [ function ] StopDragAchievementWindow

