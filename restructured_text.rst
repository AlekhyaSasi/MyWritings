reStructuredText (reST) is the default plaintext markup language used by both Docutils and Sphinx. 
While Docutils provides the basic reStructuredText syntax, Sphinx extends this to support additional functionality.

This guide will take you through reST concepts and syntax with examples. 

::
    
    *Note*: This document is written in rst. Refer to the source to know the syntax.

But before we dive in, let's look at the differnces between reST and Markdown.

.. list-table:: 
   :widths: 50 50
   :header-rows: 1

   * - Markdown
     - reST
   * - Markdown's syntax is intended to be used as a format for writing for the web.
     - reST is specifically designed for writing technical documentation. 
   * - HTML is the way to extend it. 
     - It provides standard extension mechanisms called `directives <https://docutils.sourceforge.io/docs/ref/rst/directives.html>`_ and `roles <https://docutils.sourceforge.io/docs/ref/rst/roles.html>`_.
   * - With Markdown you can force a newline by ending a line with a backslash.
     - reST has `option lists <https://docutils.sourceforge.io/docs/user/rst/quickref.html#option-lists>`_ for listing options and args you might pass to a command-line program.
   * - Easy syntax.
     - Complicted syntax.
     
========================
Syntax:
========================

+++++
Headers
+++++


