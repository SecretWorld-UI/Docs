# [ class ] com.Utils.Text

# [ group ] Functions

# [ function ] GetTextExtent

Method that tries to mimic the getTextExtent method in the TextFormat class, for now it only returns an object with the width and height property set

## Parameters

<pre>
<em>text</em>    | :String - the knubot string or any other string                                  
<em>format</em>  | :TextFormat - the textformat to use when getting the text extent                 
<em>context</em> | :MovieClip - the context to create the textfield in, useful to get the textformat
</pre>

## Returns

Object - an object with the property, width and height set 

---

# [ function ] AddThousandsSeparator

This method returns a string of formatted numbers with commas inserted in the thousands place for readability.

---

