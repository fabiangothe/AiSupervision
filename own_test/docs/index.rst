.. Working test documentation master file, created by
   sphinx-quickstart on Wed Jan 25 14:48:14 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Working test's documentation!
========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


sphinx-sqlalchemy
=================

Sphinx extension for documenting SQLAlchemy ORMs.

Example
-------

::

    .. sqla-model:: ../test_example.User

    .. sqla-model:: ~../test_example.Address


.. sqla-model:: ../test_example.User

.. sqla-model:: ~../test_example.Address

This was created from:

.. literalinclude:: ../test_example.py
    :lines: 1-

