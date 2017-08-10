# [ class ] com.GameInterface.InventoryBase

One instance of this class represent an inventory. First you create it, then you regsiter it, then you use it, and in the end when about to delete it, you unregister it. The idea is that you should extend/inherit from this class. Override the empty callback functions, like ItemAdded and such, to do your stuff.

---

# [ group ] Variables

# [ variable ] m_Items

This is the array of items in this inventory. The arrays size represent the maxsize of this inventory. The size may change. Signals will be sent in that case. Gamecode handles the members and content will automaticaly change to reflect the GC inventory. Signals will be sent right after changes has occurred to the array. The array is populated with com.GameInterface.InventoryItem objects.

---

# [ group ] Properties

# [ property ] m_InventoryID

Type of inventory. ex. Enums.InvType.e_Type_GC_WeaponContainer is what you wear. e_Type_GC_WeaponContainer e_Type_GC_BackpackContainer e_Type_GC_BankContainer e_Type_GC_ChestContainer e_Type_GC_TradeContainer e_Type_GC_GuildContainer e_Type_GC_OverflowContainer e_Type_GC_ShopContainer e_Type_GC_ResourceContainer e_Type_GC_QuestContainer e_Type_MailInventory e_Type_LootInventory e_Type_GC_BeltInventory e_Type_GC_TradepostContainer

---

# [ group ] Functions

# [ function ] InventoryBase

Constructor.

---

# [ function ] AddItem

Move an item from an inventory to another or the same. Note that when you add the item to the wear inventory (e_Type_GC_WeaponContainer) you can use dstPos = Enums.ItemEquipLocation.Wear_DefaultLocation to put the item at it's default location.

## Parameters

<pre>
<em>srcInv</em> | [in]  The inventory the move was done from.                                                             
<em>srcPos</em> | [in]  The pos the item came from.                                                                       
<em>dstPos</em> | [in]  The position the item will have in this inventory.                                                
<em>param</em>  |         [out] Returns an enum indicating if the move succeed or if it's not done yet (it's in a dialog).
</pre>

---

# [ function ] PreviewItem

# [ function ] PreviewCharacter

# [ function ] DeleteItem

Delete an item from this inventory. A confirmation dialog box will be shown from gamecode as a security meassure.

## Parameters

<pre>
<em>itemPos</em> | [in]  The item to delete.
</pre>

---

# [ function ] UseItem

Tries to use the given item.

## Parameters

<pre>
<em>itemPos</em> | [in]  The item to use.
</pre>

---

# [ function ] CanAddItemToShortcuts

# [ function ] SplitItem

Tries to split a given item

## Parameters

<pre>
<em>srcInvID</em> | [in] The id of the source inventory                           
<em>srcPos</em>   | [in]  The item to split.                                      
<em>dstPos</em>   | [in]  where to split it to.                                   
<em>itemPos</em>  | [in]  How much to split (How big will the resulting stack be).
</pre>

---

# [ function ] MakeItemLink

Tries to make a item link of the given item

## Parameters

<pre>
<em>itemPos</em> | [in]  The item to make item link of.
</pre>

---

# [ function ] GetFirstFreeItemSlot

# [ function ] GetMaxItems

# [ function ] GetInventoryID

# [ function ] IsInitialized

# [ function ] CreateItem

# [ function ] GetItemXPForLevel

# [ function ] CreateACGItemFromTemplate

# [ group ] Variables

# [ variable ] SignalItemLoaded

Called from gamecode when an item is finished async loaded at the given pos.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The position for this new item.                          
</pre>

---

# [ variable ] SignalItemAdded

Called from gamecode when an item is added to this inventory at the given pos. This will be called both when you get an item and if an item is moved from a different inventory to this.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The position for this new item.                          
</pre>

---

# [ variable ] SignalItemMoved

Called from gamecode when an item is moved within this inventory. If the toPos contains an item, then the two items swap position.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>fromPos</em>     | [in]  Where the item was moved from.                           
<em>toPos</em>       | [in]  The items new position.                                  
</pre>

---

# [ variable ] SignalItemRemoved

Called from gamecode when an item is removed from this inventory, either as a move or as a delete.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  Where the item was removed from.                         
<em>moved</em>       | [in]  True if the item moved to some other inventory.          
</pre>

---

# [ variable ] SignalItemChanged

Called from gamecode when an item changed somehow.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The item in question.                                    
</pre>

---

# [ variable ] SignalItemStatChanged

Called from gamecode when a stat on an item changes.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  Item in question.                                        
<em>stat</em>        | [in]  The stat that changed.                                   
<em>newValue</em>    | [in]  The new value of for this stat.                          
</pre>

---

# [ variable ] SignalInventoryExpanded

Called from gamecode when the inventory is expanded.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal                       
<em>newSize</em>     | [in]  The new total size of the inventory. The m_Items will already have the new size.
</pre>

---

# [ variable ] SignalItemCooldown

Called from gamecode when an item is on cooldown.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The position in the inventory the item is                
<em>seconds</em>     | [in]  the number of seconds left in cooldown                   
</pre>

---

# [ variable ] SignalItemCooldownRemoved

Called from gamecode when an item is removed from cooldown.

## Parameters

<pre>
<em>inventoryID</em> | :com.Utils.ID32 [] identity of the inventory sending the signal
<em>itemPos</em>     | [in]  The position in the inventory the item is                
</pre>

---

