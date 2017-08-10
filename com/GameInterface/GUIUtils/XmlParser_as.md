# [ class ] com.GameInterface.GUIUtils.XmlParser

Parses XML to values in an object and handles methods for simple retrieval of these values

---

# [ group ] Variables

# [ variable ] m_Values

# [ group ] Functions

# [ function ] XmlParser

The constructor, retrives an XMLNode, sets up the toplevel object and starts parsing the xml

## Parameters

<pre>
<em>p_xml</em> | :XMLNode - the fragment xml to parse
</pre>

## Returns

void

---

# [ function ] recursiveXmlLoop

Recursive looping and parsiing of XML, parses the attributes first if available, proceeds with the elements, if any sub elements the function calls itself repeditly

## Parameters

<pre>
<em>p_xmlnode</em>     | :XMLNode - the xmlnode to parse                                                            
<em>p_valueobject</em> | :Object -  the Object at the correct point where you wuuld like to insert the parsed values
</pre>

## Returns

Void

---

# [ function ] getAttributes

Reads all the attributes of an XML, if attribute is empty it is omitted

## Parameters

<pre>
<em>p_xmlnode</em>     | :XMLNode - the xmlnode to parse                                                            
<em>p_valueobject</em> | :Object -  the Object at the correct point where you would like to insert the parsed values
</pre>

## Returns

Object - the object (or associative array if you will ) where the values are inserted

---

# [ function ] GetValue

Looks up the internal getValueByName method and return its values

## Parameters

<pre>
<em>p_name</em> | :String
</pre>

## Returns

string, null or Object depending if one, zero or multiple items are found

---

# [ function ] getValueByName

recursive function that loops the m_Values object looking for textual matches, and returns all possible

## Parameters

<pre>
<em>p_name</em>        | :String - the name of the prop to return
<em>p_valueobject</em> | :Object -  the object you are inspecting
</pre>

## Returns

string, null or Object depending if one, zero or multiple items are found

---

# [ function ] hasAttribute

attempts to iterate the XMLNode's attributes, returns true if there are any attributes to iterate

## Parameters

<pre>
<em>p_context</em> | :XMLNode - the xmlnode to inspact for attributes
</pre>

## Returns

Boolean true if attributes exist, false if not

---

