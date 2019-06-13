
*************
rst:directive
*************

Example::

    .. rst:directive:: foo

Describes a reST directive.  The *name* can be a single directive name or
actual directive syntax (`..` prefix and `::` suffix) with arguments that
will be rendered differently.  For example::

    .. rst:directive:: foo

        Foo description.

    .. rst:directive:: .. bar:: baz

        Bar description.

will be rendered as:

    .. rst:directive:: foo

        Foo description.

    .. rst:directive:: .. bar:: baz

        Bar description.
