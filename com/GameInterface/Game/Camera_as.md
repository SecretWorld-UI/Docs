# [ class ] com.GameInterface.Game.Camera

# [ group ] Variables

# [ variable ] m_Pos

These static variables are updated every 0.5 sec with info about cameras current posistion and rotation. NOTE: You must first call RequestCameraPosRotUpdates( true ) once to start the timer.

---

# [ variable ] m_AngleY

The cameras angle around the y axis. In radians.

---

# [ variable ] m_CinematicStripHeight

The height of one black part of the cinematic letterbox. This number is always up to date.

---

# [ variable ] SignalCinematicActivated

Signal send when cinematic is started or ended.

## Parameters

<pre>
<em>activated</em> | :Number       1 if started, 0 if ended.
</pre>

---

# [ group ] Functions

# [ function ] RunCameraPath

Runs a camerapath.

## Parameters

<pre>
<em>pathName</em>                   | :String                     Path to play.  
<em>switchToDefaultCamWhenDone</em> | :Boolean  Set camera back?                 
<em>initialPosition</em>            | :Number              Start pos on the path.
<em>targetPosition</em>             | :Number               End pos on the path. 
</pre>

---

# [ function ] PlaceCamera

Place the cinematic camera at a position looking at something.

## Parameters

<pre>
<em>posX</em>    | :Number      The new position of the camera in world coordinates.
<em>offsetX</em> | :Number   The position to look at in world coordinates.          
</pre>

---

# [ function ] SetFOV

Set field of view for the cinematic camera.

## Parameters

<pre>
<em>fov</em> | :Number      The fov. Hopefully reset everytime a new cinematic is started.
</pre>

---

# [ function ] RequestCameraPosRotUpdates

Tell gamecode to start filling m_Pos and m_AngleY every interval.

## Parameters

<pre>
<em>startUpdates</em> | :Boolean      True to start it, false to end it.
</pre>

---

# [ function ] GetZoom

Get the zoom position of the camera

---

