# [ class ] com.GameInterface.Dynels

Signals regarding stats and buffs on any character, Wraps the ASDynels.cpp for actionscript

---

# [ group ] Variables

# [ variable ] Slots

The DynelSlot object is never removed as it represent directly to the slots defined by Enums.DynelSlot so you can always keep connections to the signals and never change them. Use Exists() if you need to check that the slot holds some dynel.

---

# [ variable ] SlotChanged

Signal dispatched when a change to a slot is discovered (that is that a target is being replaced, added or removed)

## Parameters

<pre>
<em>p_Slot</em>   | :Number  -  The slot id                 
<em>p_Exists</em> | :Booelan - True if the slot has a dynel.
</pre>

---

# [ variable ] DynelGone

Dispatched when a registered object is removed from the client.

## Parameters

<pre>
<em>type</em>     | :Number -  The type for the object     
<em>instance</em> | :Number  -  The instance for the object
</pre>

---

