# [ class ] com.GameInterface.DynelsBase

# [ group ] Functions

# [ function ] RegisterProperty

Use this call to ask for some values to be update each frame for the dynel defined by type and instance. You will get a object variable back that wuill have some fields filled depending on the enum you use. The object you get back will always be the same if you do multiple calls to this function. The object will have the wanted values filled already on return, ready to use. If the dynel is removed from the pf, you'll get DynelGone signal with the type and instance. Then you don't have to unregister. Use UnregisterProperty(...) when you no longer need the updates. Note that each property is refcounted so if you register the same dynel and enum from 2 different modules, you will also have to unregister both to make the update stop. Enums and which members they will fill: Property::e_ObjPos             /// Position.                                             Members:  PosX, PosY, PosZ Property::e_ObjScreenPos       /// Screen pos of the object and distance to camera.      Members:  ObjScreenPosX, ObjScreenPosY Property::e_MissionScreenPos   /// Screen pos of the mission selector and distance to camera.      Members:  MissionScreenPosX, MissionScreenPosY, CamDistance, m_PosBlocked

## Parameters

<pre>
<em>type</em>     | [in]  The type of objects     
<em>instance</em> | [in]  The objects instance    
<em>enum</em>     | [in]  The property to ask for.
<em>param</em>    |          [out] Object         
</pre>

---

# [ function ] UnregisterProperty

Stop the update from the earlier registered dynel.

## Parameters

<pre>
<em>type</em>     | [in]  The type of objects                
<em>instance</em> | [in]  The objects instance               
<em>enum</em>     | [in]  The property to stop updateing for.
</pre>

---

# [ function ] SetTarget

Target something in a slot. This is restricted to slots only to avoid macroing. The slot will end up as a hostile or friendly target all depending on it's carsgroup.

## Parameters

<pre>
<em>slot</em> | [in]  The slot to target.
</pre>

---

# [ function ] RefreshBuffs

# [ function ] Trade

Start trade with the given id.

---

# [ function ] InviteToGuild

Invite player to guild.

---

# [ function ] PromoteGuildMember

Promote a member of your guild.

---

# [ function ] DemoteGuildMember

Demote a member of your guild

---

