# [ file ] ResourceWindow.as

# [ group ] Variables

# [ variable ] LEFT

# [ variable ] RIGHT

# [ variable ] NONE

# [ variable ] m_WeaponInventory

# [ variable ] m_RightResource

# [ variable ] m_LeftResource

# [ variable ] m_Character

# [ variable ] m_CharacterId

# [ variable ] m_LeftPos

# [ variable ] m_RightPos

# [ variable ] m_MaxCounter

# [ variable ] m_MinCounter

# [ variable ] m_Resources

# [ variable ] m_Scale

# [ variable ] m_IsPlayerCharacter

# [ group ] Functions

# [ function ] Init

called from the onload method. one call for the lifetime of this clip

---

# [ function ] SetCharacter

static mapping of all resources

---

# [ function ] GetResource

map the weapon type to the correct weapon

## Parameters

<pre>
<em>weaponType</em> | :Number, the m_Type property of the inventoryItem contained in the equipped inventory
</pre>

## Returns

Number - the resource mapped to this weapon or 0 on erroe, the 0 will be catched later if this error occur

---

# [ function ] SetResourcesVisibility

# [ function ] AddResource

# [ function ] Layout

updates the resources on stage with their counters

---

# [ function ] ClearResource

removes the resource indicator from stage without modifying the resource object

## Parameters

<pre>
<em>resourceSide</em> | :String  - The side (left or right)
</pre>

---

# [ function ] SlotResourceUpdated

param resourceType:Number    The resource type (1-9).

## Parameters

<pre>
<em>resourceAmount</em> | :Number  The new resource amount.
<em>targetID</em>       | :ID32          The target        
</pre>

---

# [ function ] IsResourceVisible

checks to see if there is a resource indicator on stage for this resource allready

## Parameters

<pre>
<em>resource</em> | :Number - the resource to check
</pre>

## Returns

Boolean - if resource is on stage or not

---

# [ function ] SlotWeaponRemoved

param inventoryID:com.Utils.ID32 [] identity of the inventory sending the signal

## Parameters

<pre>
<em>itemPos</em> | [in]  Where the item was removed from.               
<em>moved</em>   | [in]  True if the item moved to some other inventory.
</pre>

---

# [ function ] SlotWeaponAdded

This will be called both when you get an item and if an item is moved from a different inventory to this.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The position for this new item.                          
</pre>

---

# [ function ] SlotWeaponChanged

# [ function ] IsSelfWeaponResource

