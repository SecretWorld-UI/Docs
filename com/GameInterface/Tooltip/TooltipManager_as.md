# [ class ] com.GameInterface.Tooltip.TooltipManager

# [ group ] Variables

# [ variable ] m_instance

# [ variable ] m_WindowIndex

# [ group ] Functions

# [ function ] GetInstance

# [ function ] TooltipManager

# [ function ] ShowTooltip

Display a tooltip. ShowTooltip() opens a tooltip window displaying the data from tooltipData and the optional 4th argument that can be an array of additional TooltipData objects that will be displayed next to the main tooltip (used for comparision mode). The first argument (targetClip) can be either null or a MovieClip. If it is null the tooltip arrow will point towards the current mouse position. If targetClip is a valid MovieClip the arrow will point at the edge of this clip. The clip can be moved later with TooltipInterface.SetPosition(). The orientation argument specify wether the different panels should be layed out vertically (TooltipInterface.e_OrientationVertical) or horizontally (TooltipInterface.e_OrientationHorizontal) when displaying multiple panels.

The return value is a TooltipInterface that will be the interface for further interaction with the tooltip. Through this interface you can move the tooltip, convert it into a floating window with a close button or close it.

---

