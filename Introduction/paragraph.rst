Paragraph
=========


Paragraphs contain text and may contain inline markup:
*emphasis*, **strong emphasis**, `interpreted text`, ``inline
literals``, standalone hyperlinks (http://www.python.org),
external hyperlinks (Python_), internal cross-references
(example_), footnote references ([1]_), citation references
([CIT2002]_), substitution references (|example|), and _`inline
internal targets`.

Paragraphs are separated by blank lines and are left-aligned. Adding the following will change the appearance of the above...

footnote reference

.. [1] A footnote contains body elements, consistently
   indented by at least 3 spaces.

citations

.. [CIT2002] Just like a footnote, except the label is
   textual.

external hyperlinks

.. _Python: http://www.python.org


substitution definition

.. |examples| image:: ./images/picture.png

.. Comments begin with two dots and a space.  Anything may
   follow, except for the syntax of footnotes/citations,
   hyperlink targets, directives, or substitution definitions.

+------------------------------+
| paragraph                    |
|                              |
+------------------------------+

:Date: 2001-08-16
:Version: 1
:Authors: - Me
          - Myself
          - I
:Indentation: Since the field marker may be quite long, the second
   and subsequent lines of the field body do not have to line up
   with the first line, but they must be indented relative to the
   field name marker, and they must line up with each other.
:Parameter i: integer

::
    this has the colon-colon thing

Paragraph:

::

    Literal block


Paragraph: ::

    Literal block

Paragraph::

    Literal block
    *italics*

John Doe wrote::

>> Great idea!
>
> Why didn't I think of that?

You just did!  ;-)

**line blocks**

| Lend us a couple of bob till Thursday.
| I'm absolutely skint.
| But I'm expecting a postal order and I can pay you back
  as soon as it comes.
| Love, Ewan.

example

Take it away, Eric the Orchestra Leader!

    | A one, two, a one two three four
    |
    | Half a bee, philosophically,
    |     must, *ipso facto*, half not be.
    | But half the bee has got to be,
    |     *vis a vis* its entity.  D'you see?
    |
    | But can a bee be said to be
    |     or not to be an entire bee,
    |         when half the bee is not a bee,
    |             due to some ancient injury?
    |
    | Singing...


