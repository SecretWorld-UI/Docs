# [ class ] com.GameInterface.Lore

# [ group ] Variables

# [ variable ] s_LoreCache

# [ variable ] s_FilteredLoreCache

# [ group ] Functions

# [ function ] GetCachedNode

# [ function ] ClearCache

# [ function ] GetLoreTree

# [ function ] GetAchievementTree

# [ function ] GetTitleTree

# [ function ] GetTutorialTree

# [ function ] GetPetTree

# [ function ] GetSeasonalAchievementTree

# [ function ] GetMountTree

# [ function ] GetTeleportTree

# [ function ] GetEmoteTree

# [ function ] RecursiveLoadNode

# [ function ] GetCountForNodeId

# [ function ] GetTitleArray

# [ function ] RecursiveFillTitleArray

# [ function ] GetFactionRankArray

# [ function ] RecursiveFillFactionTitleArray

# [ function ] IsLeafNode

param node:LoreNode - the node to inspect

## Returns

Boolean, is it a leaf node or not

---

# [ function ] GetFirstNonLeafNode

# [ function ] GetDataNodeById

iterates the LoreNode Object and its children returning the LoreNode specified by ID

## Parameters

<pre>
<em>id</em>   | :Number - the id of the object to look for         
<em>data</em> | :Array - the list of objects and children to search
</pre>

---

# [ function ] RecursiveFindNode

# [ function ] GetTagCategory

# [ function ] GetRewardItemNameArray

# [ function ] GetDepth

# [ function ] IsSeasonalAchievementAvailable

# [ function ] ShouldShowGetAnimation

# [ function ] GetCurrentFactionRankNode

faction ranks and pets

---

# [ function ] GetNextFactionRankNode

