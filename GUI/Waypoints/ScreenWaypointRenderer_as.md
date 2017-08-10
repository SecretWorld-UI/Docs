# [ file ] ScreenWaypointRenderer.as

# [ group ] Variables

# [ variable ] m_MovieClipLoader

# [ variable ] m_RenderedWaypoints

# [ variable ] m_RenderedStackingWaypoints

# [ variable ] m_RenderedStackingWaypointsCount

# [ variable ] m_StageWidth

# [ variable ] m_WpPosLeftYBase

# [ variable ] m_WpPosRightYBase

# [ variable ] m_WpPosLeftY

# [ variable ] m_WpPosRightY

# [ variable ] m_PlayfieldID

# [ variable ] m_CurrentPFInterface

# [ variable ] m_WaypointPadding

# [ group ] Functions

# [ function ] ResizeHandler

# [ function ] Init

# [ function ] SlotPlayfieldChanged

When playfield changes we need to connect to a different playfieldwaypoints interface, and get its waypoints

---

# [ function ] SlotWaypointAdded

Adds a waypoint to the screenrenderer. Adds waypoints depending on which type

---

# [ function ] SlotWaypointRemoved

# [ function ] RemoveWaypoint

# [ function ] SlotWaypointMoved

# [ function ] SlotWaypointStateChanged

# [ function ] SlotWaypointColorChanged

# [ function ] SlotWaypointRenamed

# [ function ] UpdateScreenWaypoints

# [ function ] onEnterFrame

