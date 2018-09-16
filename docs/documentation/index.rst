#########################
Documentation Style Guide
#########################

Documentation as Code enables the ability to use a VCS with our documentation and use the `Github Flow with Forks`_.

We leverage the `RST <http://docutils.sourceforge.net/rst.html>`_ markup for documentation
as it is expressive enough for complex documentation without be intrusive.
(Markdown may be used for notes, readmes, etc, but is not suitable for proper documentation).
Be sure to visit the `reStructuredText Primer <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_.

`Sphinx <http://www.sphinx-doc.org>`_ is used to generate our documentation. It has a large community and many integrations.

We follow the `Python’s Style Guide for documenting <https://devguide.python.org/documenting/#style-guide>`_ conventions:

Key take aways include:

* All reST files use an indentation of 3 spaces; no tabs are allowed. The maximum line length is 80 characters for normal text, but tables, deeply indented code samples and long links may extend beyond that. Code example bodies should use normal Python 4-space indentation.
* The documentation focuses on affirmatively stating what the language does and how to use it effectively.
* More documentation is not necessarily better documentation. Err on the side of being succinct.
* Short code examples can be a useful adjunct to understanding. People learn faster with concrete, motivating examples that match the context of a typical use case.

We also follow `Python's Documentation for Sections <https://devguide.python.org/documenting/#sections>`_:

* # with overline, for parts
* * with overline, for chapters
* =, for sections
* -, for subsections
* ^, for subsubsections
* ", for paragraphs

.. code-block:: rst

    ##########
    Part Title
    ##########

    *************
    Chapter Title
    *************

    Section
    =======

    Sub-Section
    -----------

    Sub-Sub-Section
    ^^^^^^^^^^^^^^^

    Paragraphs
    """"""""""
