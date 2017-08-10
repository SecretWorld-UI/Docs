# [ class ] com.GameInterface.SpellBase

# [ group ] Variables

# [ variable ] m_SpellList

Associavite array of all the spells the player has. This object is supposed to be const, but that is not supported in actionscript. This list will be kept in sync by gamecode. You will get signals when the state of the list changes. Members are of type SpellData

---

# [ variable ] m_PassivesList

Members are of type PassiveData

---

# [ group ] Functions

# [ function ] EquipPassiveAbility

Equip a passive ability in a given slot

## Parameters

<pre>
<em>abilityPos</em> | :Number   The position on the bar.
<em>abilityId</em>  | :Number   The ability to auto add.
</pre>

---

# [ function ] UnequipPassiveAbility

Unequip a passive ability in a given slot

## Parameters

<pre>
<em>abilityPos</em> | :Number   The position on the bar.
</pre>

---

# [ function ] MovePassiveAbility

Moves a passive ability between two slots

## Parameters

<pre>
<em>fromPos</em> | :Number   The slot to move it from.
<em>toPos</em>   | :Number   The slot to move it to.  
</pre>

---

# [ function ] GetPassiveAbility

Gets the passive ability equipped on a given slot

## Parameters

<pre>
<em>abilityPos</em> | :Number   The slot number.
</pre>

---

# [ function ] EnterPassiveMode

Gets the passive ability equipped on a given slot

## Parameters

<pre>
<em>abilityPos</em> | :Number   The slot number.
</pre>

---

# [ function ] ExitPassiveMode

Gets the passive ability equipped on a given slot

## Parameters

<pre>
<em>abilityPos</em> | :Number   The slot number.
</pre>

---

# [ function ] CancelBuff

Cancels a specific buff

## Parameters

<pre>
<em>buffId</em> | :Number   The buffid.
</pre>

---

# [ function ] IsTokenState

# [ function ] IsPassiveEquipped

# [ function ] GetSpellDescription

# [ function ] GetSpellData

# [ function ] GetBuffData

# [ function ] GetStat

# [ function ] GetSpellShortDescription

# [ function ] GetSpellStaticDescription

# [ function ] SummonPetFromTag

# [ function ] SummonMountFromTag

# [ function ] CastTeleportFromTag

# [ function ] CastEmoteFromTag

# [ function ] ActivateNotification

# [ group ] Variables

# [ variable ] SignalSpellUpdate

Signal sent when the spell list is updated from server. m_SpellList will now contain all your spells.

---

# [ variable ] SignalSpellLearned

Signal sent when a new spell has been learned. m_SpellList will now contain the id.

---

# [ variable ] SignalSpellForgotten

Signal sent when a spell has been removed. m_SpellList will no longer contain the id.

---

# [ variable ] SignalPassiveUpdate

Signal sent when the passives list is updated from server. m_PassivesList will now contain all your spells.

---

# [ variable ] SignalPassiveLearned

Signal sent when a new spell has been learned. m_PassivesList will now contain the id.

---

# [ variable ] SignalPassiveForgotten

Signal sent when a spell has been removed. m_PassivesList will no longer contain the id.

---

# [ variable ] SignalPassiveAdded

# [ variable ] SignalPassiveRemoved

# [ variable ] SignalSpellbookReceived

