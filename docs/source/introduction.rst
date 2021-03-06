Introducing dtoolAI
===================

What is dtoolAI?
----------------

dtoolAI is a Python library to make reproducible AI model training and use
easier. The dtoolAI package provides:

* A Python API to a set of classes and helper functions for managing Deep
  Learning model data, training and use.
* Scripts and command line functions for demonstrating use and automating
  common tasks.
* Documentation in the form of both these documents and  Jupyter notebooks that
  show how to use the library.

In general, the documentation and scripts use image recognition to demonstrate
the library, but the lower level functions for packaging data and models, as
well as capturing training metadata can be used for a wide range of problem
domains.

dtoolAI makes use of `dtool <https://dtool.readthedocs.io>`_, a library for lightweight
data management to work with different data sources such as S3, Azure, HTTP and
local filesystem. dtoolAI uses `pytorch <https://pytorch.org>`_ for implementation of
AI models.

.. image:: images/dtoolAI-architecture.png 