# [ class ] GUI.Debug.Debug

# [ group ] Variables

# [ variable ] m_Instance

# [ group ] Functions

# [ function ] OpenDebugWindow

Loads a new instance of a debug window.

---

# [ function ] TraceObject

Trace an object from chatline. Ex.1  /aseval com.Utils.Debug.TraceObject _root 6 movieclip This will show all movieclips and their childs down to a depth of 6. Will show movieclip x,y,w,h,vis,alp. Ex.2  /aseval com.Utils.Debug.TraceObject _global.Game.Quests.m_PlayerTiers 2 Will show 2 layers of the playertiers objects.

<pre>
<em>path</em>  | Full path to the object. 
<em>depth</em> | Number of depths to show.
<em>type</em>  | "movieclip" or nothing.  
</pre>

---

# [ function ] RecurseObject

Use TraceObject(..) if you can. Recurse an object to show all it's properties. Internal function, but can be used when debugging code if you don't have the full path to the object and TraceObject can't be used.

<pre>
<em>path</em>  | Full path to the object. 
<em>depth</em> | Number of depths to show.
<em>type</em>  | "movieclip" or nothing.  
</pre>

---

# [ function ] TraceHitTest

Checks what object the mouse is currently over and traces it's full path.

---

# [ function ] RecurseHitTest

Use TraceObject(..) if you can. Recurse an object to show all it's properties. Internal function, but can be used when debugging code if you don't have the full path to the object and TraceObject can't be used.

<pre>
<em>name</em> | The name of the object.
<em>root</em> | The object             
</pre>

---

