.. _utils:

************************************************
Astropy Core Package Utilities (`astropy.utils`)
************************************************

Introduction
============

The `astropy.utils` package contains general-purpose utility functions and
classes.  Examples include data structures, tools for downloading and caching
from URLs, and version intercompatibility functions.

This functionality is not astronomy-specific, but is intended primarily for
use by Astropy developers. It is all safe for users to use, but the functions
and classes are typically more complicated or specific to a particuly need of
Astropy.

Because of the mostly standalone and grab-bag nature of these utilities, they
are generally best understood through their docstrings, and hence this
documentation does not have detailed sections like the other packages.

.. note::
    The `astropy.utils.compat` subpackage is not included in this
    documentation. It contains utility modules for compatibility with
    older/newer versions of python, as well as including some bugfixes
    for the stdlib that are important for Astropy. It is recommended
    that developers at least glance over the source code for this
    subpackage, but it cannot be reliably included here because of the
    large amount of version-specific code it contains.


Reference/API
=============

.. automodapi:: astropy.utils.misc
    :no-inheritance-diagram:

.. automodapi:: astropy.utils.exceptions
    :no-inheritance-diagram:

.. automodapi:: astropy.utils.collections
    :no-inheritance-diagram:

.. automodapi:: astropy.utils.console
    :no-inheritance-diagram:

.. automodapi:: astropy.utils.timer
    :no-inheritance-diagram:

File Downloads
--------------

.. automodapi:: astropy.utils.data
    :no-inheritance-diagram:

XML
---
The ``astropy.utils.xml.*`` modules provide various
`XML <http://www.w3.org/XML/>`_ processing tools.

.. automodapi:: astropy.utils.xml.check
    :no-inheritance-diagram:
    :headings: ^"

.. automodapi:: astropy.utils.xml.iterparser
    :no-inheritance-diagram:
    :headings: ^"

.. automodapi:: astropy.utils.xml.validate
    :no-inheritance-diagram:
    :headings: ^"

.. automodapi:: astropy.utils.xml.writer
    :no-inheritance-diagram:
    :headings: ^"




