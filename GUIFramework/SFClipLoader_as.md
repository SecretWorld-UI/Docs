# [ class ] GUIFramework.SFClipLoader

# [ group ] Variables

# [ variable ] m_Loader

# [ variable ] m_CurrentScreenRes

# [ variable ] m_NextClipID

# [ group ] Functions

# [ function ] SetupLoader

# [ group ] Variables

# [ variable ] SignalDisplayResolutionChanged

# [ variable ] SignalFrameStarted

# [ group ] Functions

# [ function ] OnScreenResChanged

# [ function ] CreateEmptyMovieClip

# [ function ] LoadClip

# [ function ] AddClip

# [ function ] UnloadClip

# [ function ] FindClipByPos

Returns the index of the topmost toplevel clip that intersects with (x,y). If no clip intersects -1 is returned.

---

# [ function ] GetClipIndex

Search the list of toplevel clips for \a movie. If found the index is returned, if not -1 is returned.

---

# [ function ] MoveToFront

Move the clip at position \a index to the frontmost position within it's sorting layer. I.e. in front of all other clips with equal depth layer and sub depth as itself.

---

# [ function ] SetClipLayer

# [ function ] AddClipNode

Add a movie clip to the list of toplevel clips, and sort it according to depth layer and sub depth. This function should only be useed by GUIFramework.swf.

---

# [ function ] RemoveClipByIndex

Remove a movie clip to the list of toplevel clips. This function should only be useed by GUIFramework.swf.

---

# [ function ] RemoveClipNode

# [ function ] OnLoadInit

# [ function ] UpdateClipSize

# [ function ] OnLoadComplete

# [ function ] OnLoadError

# [ function ] AddModalBlocker

# [ function ] RemoveModalBlocker

# [ function ] MakeClipModal

# [ function ] PrintTopLevelClipsDebug

# [ group ] Variables

# [ variable ] s_TopLevelClips

# [ variable ] s_ModalClips

