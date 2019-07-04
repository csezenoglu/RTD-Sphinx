cite*
*****

.. warning::

    sphinxcontrib-bibtex extension is required.

.. rst:role:: cite

   Create a citation to a bibliographic entry. For example:

   .. code-block:: rest

      See :cite:`1987:nelson` for an introduction to non-standard analysis.

   which would be equivalent to the following LaTeX code:

   .. code-block:: latex

      See \cite{1987:nelson} for an introduction to non-standard analysis.

   Multiple comma-separated keys can be specified at once:

   .. code-block:: rest

      See :cite:`1987:nelson,2001:schechter`.
