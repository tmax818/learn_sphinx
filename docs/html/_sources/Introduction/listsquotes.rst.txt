Lists and Quote-like blocks
===========================

**A list:

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

**Another list:

1. This is a numbered list.
2. It has two items too.

**This one uses #'s:

#. This is a numbered list.
#. It has two items too.

**Nested lists must be separated from the parent list items by blank lines:

* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues


**field lists**

:what: Field lists map field names to field bodies, like
       database records.  They are often part of an extension
       syntax.

:how: The field marker is a colon, the field name, and a
      colon.

      The field body may contain one or more body elements,
      indented relative to the field marker.