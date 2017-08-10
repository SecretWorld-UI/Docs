# [ class ] com.GameInterface.Input

# [ group ] Functions

# [ function ] RegisterHotkey

Register a hotkey to call a static actionscript function on key up/down. Example:    com.GameInterface.Input.RegisterHotkey( Enums.InputCommand.e_InputCommand_Debug_FramerateToggle, "FramerateView.ToggleFramerate", Enums.Hotkey.eHotkeyDown ,0 )

## Parameters

<pre>
<em>input</em>            | [in] The input enum. Ex. Enums.InputCommand.                                                                                                                                                                        
<em>callbackFunction</em> | [in] The static actionscript function to call when hotkey is pressed. Ex. "Game.Abilityview.ActivateItem". It takes 2 param, the hotkey enum as Number and the Enums.Hotkey state. To reset, set it to empty string.
<em>hotkeyState</em>      | [in] The state the hotkey should be in. Enums.Hotkey.eHotkeyDown / Enums.Hotkey.eHotkeyUp                                                                                                                           
<em>GMFlags</em>          | [in] What gmflags must be set to use this hotkey.                                                                                                                                                                   
</pre>

---

