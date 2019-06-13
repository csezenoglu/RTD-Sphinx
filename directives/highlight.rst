
*********
highlight
*********

Example::

    .. highlight:: ccc

This language is used until the next ``highlight`` directive is encountered.
As discussed previously, *language* can be any lexer alias supported by
Pygments.

**Additional options**

Pygments can generate line numbers for code blocks.  To enable this, use the
``linenothreshold`` option. ::

    .. highlight:: python
        :linenothreshold: 5

This will produce line numbers for all code blocks longer than five lines.

To ignore minor errors on highlighting, you can specifiy ``:force:`` option.

.. versionchanged:: 2.1

    ``:force:`` option.

----

Example-1:

The literal blocks are highlighted as HTML, until a new directive is found.

.. rubric:: Source Code

.. code-block:: none

    .. highlight:: html

    ::

    <html><head></head>
    <body>This is a text.</body>
    </html>

.. rubric:: Result

.. highlight:: html

::

<html><head></head>
<body>This is a text.</body>
</html>

----

End Examples

The following directive changes the hightlight language to SQL.

.. highlight:: sql

::

   SELECT * FROM mytable



From here on no highlighting will be done.

::

   SELECT * FROM mytable