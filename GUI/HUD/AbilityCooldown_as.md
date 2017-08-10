# [ class ] GUI.HUD.AbilityCooldown

adds the animation timer to the cooldown

---

# [ group ] Variables

# [ variable ] m_IntervalID

# [ variable ] m_Increments

# [ variable ] m_MaskHeight

# [ variable ] m_MaskY

# [ variable ] m_Mask

# [ variable ] m_CooldownFlags

# [ variable ] m_CooldownTimer

# [ variable ] m_IsPrepared

# [ variable ] m_UseTimer

# [ variable ] m_TotalDuration

# [ variable ] m_StartTime

# [ variable ] m_EndTime

# [ variable ] m_SpellId

# [ variable ] SignalDone

# [ variable ] m_Icon

# [ group ] Functions

# [ function ] AbilityCooldown

Sets up a new Abilitycooldown, subsequent calls to this instance should be done trough the AddCooldown method

---

# [ function ] PrepareStage

prepares all values and sets all variables needed in the class-wide scope note this is only to be done ONCE in the lifetime of an instance of this class

---

# [ function ] UpdateTimer

Method that updates

---

# [ function ] ClearMask

# [ function ] ApplyMask

# [ function ] OverwriteCooldown

# [ function ] EmitSignal

# [ function ] RemoveCooldown

# [ function ] GetCooldownFlags

