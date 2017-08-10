# [ class ] com.GameInterface.DynelSlot

NOTE: This object is never removed. So you can keep ref to it and keep the connections. Only the data within it changes.

---

# [ group ] Variables

# [ variable ] Name

# [ variable ] m_Id

# [ variable ] OnClient

# [ variable ] Stats

# [ variable ] Buffs

# [ variable ] StatUpdated

Signal sent any stat has been updated. Note that there exist 1 signal per Enums.DynelSlot . Use it like this:  Dynels.Slots[Enums.DynelSlot.e_Slot_Player].StatUpdated.Connect( this.m_SignalGroup, this.onStatUpdated, this );

## Parameters

<pre>
<em>p_StatEnum</em>  | :Number  -  The type of stat, defined in the Stat  Enum
<em>p_StatValue</em> | :Number -  The value of the stat                       
</pre>

---

# [ variable ] DynelOnClient

This signal is sent for team members to tell if they are visible/available on your client, or too far away. Use it for teammembers to show less info when not in range.

## Parameters

<pre>
<em>p_OnClient</em> | :Boolean  -  True if the dynel is now on the client.
</pre>

---

# [ variable ] BuffActivated

Dispatched when a buff is activated

## Parameters

<pre>
<em>p_BuffID</em>            | :Number  - The template id of the buff.                                
<em>p_BuffTotalTime</em>     | :Number - The total time the buff lasts in milliseconds.               
<em>p_BuffRemainingTime</em> | :Number  -  The remaining time of the buff at the time in milliseconds.
<em>p_Icon</em>              | :String  -  The icon string ready to be loaded.                        
<em>p_BuffName</em>          | :String  -  The friendly name of the buff                              
<em>p_Hostile</em>           | :Boolean -  The type of spell. Enums.                                  
<em>p_Count</em>             | :Number  - The number of counters if any.                              
<em>p_MaxCounters</em>       | :Number - The max number of counters.                                  
<em>p_ColorLine</em>         | :Number - The color category.                                          
</pre>

---

# [ variable ] BuffDeactivated

Dispatched when a buff is deactivated

## Parameters

<pre>
<em>p_TemplateId</em> | :Number  -  The id of the buff
</pre>

---

# [ group ] Functions

# [ function ] DynelSlot

# [ function ] Exists

Returns true if the slot is filled.

---

# [ function ] IsNpc

# [ function ] IsPlayer

# [ function ] IsSimpleDynel

# [ function ] IsDestructible

# [ function ] GetID

