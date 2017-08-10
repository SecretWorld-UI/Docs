# [ file ] MainMenuWindow.as

# [ group ] Variables

# [ variable ] STANDARD_FONT

# [ variable ] FONT_SIZE

# [ variable ] FONT_SIZE_LARGE

# [ variable ] COLOR

# [ variable ] ICON_MARGIN

# [ variable ] ICON_LABEL_Y

# [ variable ] STARTING_Y_POSITION

# [ variable ] ANIMATION_DURATION

# [ variable ] BLINK_ANIMATION_DURATION

# [ variable ] MAX_BLINK_AMOUNT

# [ variable ] GROUP_FINDER_ENABLE

# [ variable ] REGION_TELEPORT_ENABLE

# [ variable ] RECEIVE_MAIL_SOUND_EFFECT

# [ variable ] m_TDB_CharacterSheet

# [ variable ] m_TDB_AbilityWheel

# [ variable ] m_TDB_Inventory

# [ variable ] m_TDB_Journal

# [ variable ] m_TDB_PvP

# [ variable ] m_TDB_RegionTeleport

# [ variable ] m_TDB_Settings

# [ variable ] m_TDB_Shop

# [ variable ] m_TDB_Shop_DisabledTooltip

# [ variable ] m_TDB_Exit

# [ variable ] m_TDB_Achievement

# [ variable ] m_TDB_Help

# [ variable ] m_TDB_Crafting

# [ variable ] m_TDB_Petition

# [ variable ] m_TDB_Cabal

# [ variable ] m_TDB_Friends

# [ variable ] m_TDB_LFG

# [ variable ] m_TDB_Claim

# [ variable ] m_TDB_WebBrowser

# [ variable ] m_TDB_Leaderboards

# [ variable ] m_TDB_Pets

# [ variable ] m_TDB_ChallengeJournal

# [ variable ] m_TDB_GroupFinder

# [ variable ] m_TDB_Tradepost

# [ variable ] m_TDB_Membership

# [ variable ] m_TDB_TrialRemainingDays

# [ variable ] m_TDB_TrialRemainingHours

# [ variable ] m_TDB_TrialExpired

# [ variable ] m_TDB_BuyAurum

# [ variable ] m_MenuIconContainer

# [ variable ] m_MenuIcon

# [ variable ] m_MemberIconContainer

# [ variable ] m_MemberIcon

# [ variable ] m_ShopIconContainer

# [ variable ] m_ShopIcon

# [ variable ] m_TrialContainer

# [ variable ] m_TokenIconContainer_1

# [ variable ] m_TokenIcon_1

# [ variable ] m_TokenIconContainer_2

# [ variable ] m_TokenIcon_2

# [ variable ] m_TokenIconContainer_201

# [ variable ] m_TokenIcon_201

# [ variable ] m_TokenIconContainer_202

# [ variable ] m_TokenIcon_202

# [ variable ] m_TokenIconContainer_10

# [ variable ] m_TokenIcon_10

# [ variable ] m_ShardGainContainer

# [ variable ] m_LastShardGain

# [ variable ] m_FPSIconContainer

# [ variable ] m_FPSIcon

# [ variable ] m_MailIconContainer

# [ variable ] m_MailIcon

# [ variable ] m_GUILockIconContainer

# [ variable ] m_GUILockIcon

# [ variable ] m_ClockIconContainer

# [ variable ] m_ClockIcon

# [ variable ] m_DownloadingIconContainer

# [ variable ] m_DownloadingIcon

# [ variable ] m_IsMenuOpen

# [ variable ] m_Character

# [ variable ] m_CharacterSheetMonitor

# [ variable ] m_AnimaWheelMonitor

# [ variable ] m_InventoryMonitor

# [ variable ] m_JournalMonitor

# [ variable ] m_PvPMonitor

# [ variable ] m_RegionTeleportMonitor

# [ variable ] m_ItemShopMonitor

# [ variable ] m_AchievementMonitor

# [ variable ] m_HelpMonitor

# [ variable ] m_CraftingMonitor

# [ variable ] m_PetitionMonitor

# [ variable ] m_CabalMonitor

# [ variable ] m_FriendsMonitor

# [ variable ] m_LFGMonitor

# [ variable ] m_ItemShopMonitor

# [ variable ] m_ClaimMonitor

# [ variable ] m_BrowserMonitor

# [ variable ] m_LeaderboardsMonitor

# [ variable ] m_PetsMonitor

# [ variable ] m_ChallengeJournalMonitor

# [ variable ] m_GroupFinderMonitor

# [ variable ] m_TradepostMonitor

# [ variable ] m_ClockShowRealTimeMonitor

# [ variable ] m_MinimapScaleMonitor

# [ variable ] m_InvisibleButton

# [ variable ] m_CharacterSheetButton

# [ variable ] m_ExitButton

# [ variable ] m_InventoryButton

# [ variable ] m_PvPButton

# [ variable ] m_RegionTeleportButton

# [ variable ] m_SettingsButton

# [ variable ] m_JournalButton

# [ variable ] m_AnimaWheelButton

# [ variable ] m_ShopButton

# [ variable ] m_CraftingButton

# [ variable ] m_AchievementButton

# [ variable ] m_HelpButton

# [ variable ] m_CabalButton

# [ variable ] m_FriendsButton

# [ variable ] m_LFGButton

# [ variable ] m_ClaimButton

# [ variable ] m_BrowserButton

# [ variable ] m_LeaderboardsButton

# [ variable ] m_PetButton

# [ variable ] m_ChallengeJournalButton

# [ variable ] m_GroupFinderButton

# [ variable ] m_TradepostButton

# [ variable ] m_BackgroundBar

# [ variable ] m_MenuItems

# [ variable ] m_ServerFramerate

# [ variable ] m_ClientFramerate

# [ variable ] m_Latency

# [ variable ] m_CurrentDate

# [ variable ] m_Tooltip

# [ variable ] m_EscapeNode

# [ variable ] m_BlinkAmount

# [ variable ] m_ClockShowRealTime

# [ variable ] m_AnimateDownload

# [ variable ] m_UpdateInterval

# [ variable ] m_TrialEndTime

# [ variable ] m_MinimapEditModeMask

# [ variable ] m_ScryTimerActive

# [ variable ] m_ScryCounterActive

# [ variable ] m_ScryTimerCounterComboActive

# [ variable ] m_FakeScryTimer

# [ variable ] m_FakeScryCounter

# [ variable ] m_FakeScryTimerCounterCombo

# [ group ] Functions

# [ function ] onLoad

# [ function ] onUnload

# [ function ] UpdateMembershipStatus

# [ function ] UpdateMainMenuItems

# [ function ] SetupMenuItem

# [ function ] Layout

# [ function ] MainMenuToggleMouseListeners

# [ function ] SlotRollOverLatency

# [ function ] SlotRollOverMail

# [ function ] SlotRollOverDownloading

# [ function ] SlotRollOutIcon

# [ function ] SlotUpdateInterval

# [ function ] SlotStatChanged

# [ function ] FormatTrialTime

# [ function ] SlotLatencyUpdated

# [ function ] SlotServerFramerateUpdated

# [ function ] SlotClientFramerateUpdated

# [ function ] SlotNewMailNotification

# [ function ] SlotAllMailReadNotification

# [ function ] BlinkMailIcon

# [ function ] BlinkMailIconCallback

# [ function ] DownloadContent

# [ function ] AnimateDownloadingIcon

# [ function ] CheckDownloadingProgress

# [ function ] SetDotState

# [ function ] MainMenuReleaseEventHandler

# [ function ] SlotEscapePressed

# [ function ] CharacterSheetHandler

# [ function ] AnimaWheelHandler

# [ function ] OpenAnimaWheel

# [ function ] JournalHandler

# [ function ] PvPHandler

# [ function ] RegionTeleportHandler

# [ function ] AchievementHandler

# [ function ] HelpHandler

# [ function ] BrowserHandler

# [ function ] PetitionHandler

# [ function ] CraftingHandler

# [ function ] FriendsHandler

# [ function ] LFGHandler

# [ function ] GroupFinderHandler

# [ function ] CabalHandler

# [ function ] ClaimHandler

# [ function ] InventoryHandler

# [ function ] ShopHandler

# [ function ] ToggleShop

# [ function ] ToggleShopMembership

# [ function ] LeaderboardsHandler

# [ function ] PetHandler

# [ function ] ChallengeJournalHandler

# [ function ] TradepostHandler

# [ function ] OpenTradepost

# [ function ] SettingsHandler

# [ function ] ExitHandler

# [ function ] SlotCharacterSheetState

# [ function ] SlotAnimaWheelState

# [ function ] SlotInventoryState

# [ function ] SlotJournalState

# [ function ] SlotPvPState

# [ function ] SlotRegionTeleportState

# [ function ] SlotHelpState

# [ function ] SlotCraftingState

# [ function ] SlotFriendsState

# [ function ] SlotLookingForGroupState

# [ function ] SlotGroupFinderState

# [ function ] SlotItemShopState

# [ function ] SlotCabalState

# [ function ] SlotAchievementState

# [ function ] SlotClaimState

# [ function ] SlotBrowserState

# [ function ] SlotLeaderboardsState

# [ function ] SlotPetsState

# [ function ] SlotChallengeJournalState

# [ function ] SlotTradepostState

# [ function ] ToggleSprint

# [ function ] BuyAurum

# [ function ] ToggleGUILock

# [ function ] SlotToggleClockType

# [ function ] SlotClockTypeChanged

# [ function ] SlotTokenAmountChanged

# [ function ] SlotScryTimerLoaded

# [ function ] SlotScryCounterLoaded

# [ function ] SlotScryTimerCounterComboLoaded

# [ function ] SlotEnteredReticuleMode

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

