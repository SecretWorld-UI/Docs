# [ class ] com.Components.TreeViewSimpleComponent

# [ group ] Variables

# [ variable ] m_Data

# [ variable ] m_RendererLinkageId

# [ variable ] m_Width

# [ variable ] m_Height

# [ variable ] m_LevelPadding

# [ variable ] m_CurrentClip

# [ variable ] m_NameTextFormat

# [ variable ] m_StatTextFormat

# [ variable ] ID

# [ variable ] SignalClicked

# [ group ] Functions

# [ function ] TreeViewSimpleComponent

# [ function ] SetData

# [ function ] SetSize

# [ function ] SetRenderer

# [ function ] Draw

# [ function ] GoToNode

draw a background where needed

---

# [ function ] RendererClickHandler

# [ function ] CloseRenderer

# [ function ] OpenRenderer

# [ function ] Reflow

reflows and redraws the menu. All clips "below" target moves spaceChange in the _y dimension

## Parameters

<pre>
<em>target</em>      | :MovieClip - the target that expand or contracta and triggers the change
<em>spaceChange</em> | :Number - the change in height that occurs                              
</pre>

---

# [ function ] CanOpenRenderer

# [ function ] GetLevelColor

