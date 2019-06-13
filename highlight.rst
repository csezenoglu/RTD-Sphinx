
***************
.. highlight ::
***************

Usage::

    .. highlight:: language

Example::

    .. highlight:: c

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
 
