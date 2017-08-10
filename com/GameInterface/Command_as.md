# [ class ] com.GameInterface.Command

Note: Only commands that are defined to show in progress bar will be dispatched to actionscripts.

---

# [ group ] Variables

# [ variable ] SignalCommandStarted

Signal sent when a command is started.

## Parameters

<pre>
<em>name</em> | :String    The name of the command.                                
<em>type</em> | :Number    CommandType_e. Currenly not exposed. Not sure if needed.
</pre>

---

# [ variable ] SignalCommandEnded

Signal sent when a command is ended.

---

# [ variable ] SignalCommandAborted

Signal sent when a command is aborted.

---

