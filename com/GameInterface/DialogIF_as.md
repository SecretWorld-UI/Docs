# [ class ] com.GameInterface.DialogIF

# [ group ] Variables

# [ variable ] SignalShowDialog

Called when a dialog should be shown. The project has to listen to this and show their visual dialog.

---

# [ group ] Functions

# [ function ] Go

/ @param message   [in] The message to show. / @param eButtons  [in] The buttons to show. Enums.StandardButtons / @param context   [in] The context that applies for this box. This would be blank or a keyword. / @param           [out] The created DialogIF object. public static function CreateDialog( String message, Number buttons, String context ) : DialogIF;

---

# [ function ] Close

# [ function ] SetText

# [ function ] GetDialogData

# [ function ] SetAutocloseOnTeleport

# [ function ] SetAutocloseOnDeath

# [ function ] SetAutoCloseDistance

# [ function ] DisconnectAllSignals

# [ function ] SetIgnoreHideModule

# [ group ] Variables

# [ variable ] SignalSelectedAS

Called when someone clicks a button.

## Parameters

<pre>
<em>buttonId</em> | [in] The button that was pressed.                   
<em>userData</em> | [in] The userdata given when the dialog was created.
</pre>

---

# [ variable ] m_PositiveAnswer

# [ variable ] m_NegativeAnswer

# [ variable ] m_Message

# [ variable ] m_Buttons

# [ variable ] m_Window

# [ variable ] m_IgnoreHideModule

