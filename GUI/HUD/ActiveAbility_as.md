# [ class ] GUI.HUD.ActiveAbility

# [ group ] Variables

# [ variable ] FLAG_WRONG_HEAPON

# [ variable ] FLAG_CASTING

# [ variable ] FLAG_COOLDOWN

# [ variable ] m_Cooldown

# [ variable ] SignalDone

# [ variable ] m_GlowFilter

# [ group ] Functions

# [ function ] ActiveAbility

# [ function ] init

# [ function ] AddCooldown

COOLDOWNS

---

# [ function ] HasCoolDown

# [ function ] GetCoolDown

# [ function ] RemoveCooldown

fires after the cooldown is complete, creating a bright overlay The cooldown is removed and an enterframe method is set to fade out the overlay

---

# [ function ] CooldownFading

OEnterFrame method that fades out the bright overlay.

---

# [ function ] StartChanneling

CHANNELING

---

# [ function ] StopChanneling

# [ function ] ChannelingHandler

# [ function ] SetDisabled

DISPLAY METHODS

---

# [ function ] SetEnabled

# [ function ] SetAvailable

this is the baseline for all

---

# [ function ] SetRangeDisabled

# [ function ] SetMaxMomentum

# [ function ] SetResourceDisabled

# [ function ] UpdateVisuals

# [ function ] ForceUpdateVisuals

