# Serialization

A library for serialization. This library can save add-on developers some work.

## Functions included

**High-level APIs:**

* **Serialization.serialize** / **Serialization.serializeTable**: a function that serializes the given table to a string.
* **Serialization.valueToString**: a function which serializes the given value to a string.

**Lower-level APIs:**

* **Serialization.tableToString**: a function which serializes the given table to a string.
* **Serialization.makeString**: a function which creates a serialized string from given text.
* **Serialization.tableToStringWithIndention**: a function which converts a table to a string.
* **Serialization.arrayToStringWithIndention**: a function which converts an array to a string.
* **Serialization.keyValueTableToStringWithIndention**: a function which converts a key-value table to a string.
* **Serialization.makeMultiLineString**: a function which makes a multi-line string.
* **Serialization.createClosingBracketOfLevel**: a function which creates a closing bracket of given level.
* **Serialization.createOpeningBracketOfLevel**: a function which creates an opening bracket of given level.
* **Serialization.indent**: a function which indents a string.
* **Serialization.indentLine**: a function which indents a line.
