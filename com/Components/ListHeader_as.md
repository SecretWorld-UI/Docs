# [ class ] com.Components.ListHeader

# [ group ] Variables

# [ variable ] m_ListItems

# [ variable ] m_ListSize

# [ variable ] m_CurrentSize

# [ variable ] m_ListItemRenderer

# [ variable ] m_Background

# [ variable ] SORTORDER_NONE

# [ variable ] SORTORDER_ASC

# [ variable ] SORTORDER_DESC

# [ variable ] m_SelectedColor

# [ variable ] m_OverColor

# [ variable ] m_LineColor

# [ variable ] m_LineThickness

# [ variable ] SignalClicked

# [ group ] Functions

# [ function ] ListHeader

# [ function ] SetListItemRenderer

set a new itemrenderere

## Parameters

<pre>
<em>newRenderer</em> | :String - tghe name of the list item to use
</pre>

---

# [ function ] SetLineStyle

Sets a new linestyle for the dividers in the header

## Parameters

<pre>
<em>thickness</em> | :Number - thickness of line in pixels
<em>color</em>     | :Number - the new linecolor          
</pre>

---

# [ function ] SetListSize

creates a point object with the new height and width, runs layout if needed

## Parameters

<pre>
<em>height</em>      | :Number - the new height                                  
<em>width</em>       | :Number - the new width                                   
<em>forceLayout</em> | :Boolean - wether to forvce redraw with the new dimensions
</pre>

---

# [ function ] SetListItem

adds a list item to the list and draws if forced

## Parameters

<pre>
<em>param</em> |  text - name of item                                             
<em>param</em> |  id - id, easier to find, being dispatched when clicking the item
<em>param</em> |  width - the width of the item                                   
<em>param</em> |  forceLayout - draw immediately                                  
</pre>

---

# [ function ] Layout

Draws the ListHeader

---

# [ function ] RendererRollOver

rollovers

---

# [ function ] RendererRollOut

rollouts

---

# [ function ] SortItems

updates the visuals, toggles the sortordering and dispatches a signal

---

