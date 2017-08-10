# [ file ] UltimateAbility.as

# [ group ] Variables

# [ variable ] m_EditModeMask

# [ variable ] m_Slot

# [ variable ] m_HotkeyLabel

# [ variable ] m_AbilitySlot

# [ variable ] m_Character

# [ variable ] m_UsedShortcut

# [ variable ] m_BarSwapped

# [ variable ] m_Visibility

# [ variable ] m_VisibilityMonitor

# [ variable ] m_ShowHotkeys

# [ variable ] VISIBILITY_NEVER

# [ variable ] VISIBILITY_CHARGED

# [ variable ] VISIBILITY_ALWAYS

# [ variable ] ULTIMATE_ABILITY_UNLOCK

# [ group ] Functions

# [ function ] onLoad

# [ function ] OnModuleActivated

connect the signals

---

# [ function ] onUnload

# [ function ] SlotTagAdded

# [ function ] SlotStatChanged

# [ function ] SlotVisibilityChanged

# [ function ] SetVisibilityByCharge

# [ function ] SlotHotkeyChanged

# [ function ] SlotShortcutbarHotkeysVisibleChanged

# [ function ] SlotShortcutsRefresh

Signal that triggers every time the player load the game or teleports or whatever, will call the SlotShortcutAdded for every shortcut item.

---

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

Signal sent when a shortcut has been move to some other spot. This probably won't ever affect the Ultimate Ability, but pay attention just to be sure No add/remove signal will be triggered.

## Parameters

<pre>
<em>fromPos</em> | :Number   The position the item was move from.
<em>toPos</em>   | :Number     The position the item was move to.
</pre>

---

# [ function ] SlotShortcutUsed

# [ function ] SlotShortcutAddedToQueue

# [ function ] SlotShortcutRemovedFromQueue

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

# [ function ] SlotSwapShortcut

# [ function ] SwapAbilities

# [ function ] SlotSwapBar

# [ function ] SlotRestoreSwapBar

# [ function ] IsUltimateShortcut

# [ function ] SlotSetGUIEditMode

# [ function ] SlotEditMaskPressed

# [ function ] SlotEditMaskReleased

# [ function ] LayoutEditModeMask

