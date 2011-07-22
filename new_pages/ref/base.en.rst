:path: ref/base
:lang: en
:title: The Structure of Source Files

The Structure of Source Files
*****************************

All data is being kept in source files which in turn are stored in a
repository to retain history. For the web presentation, these source
files are read and put into a database.

The source data files are kept in a textual markup format called
`YAML <http://www.yaml.org>`. This format allows to describe structured
objects similar to JSON or XML but in a more human readable and, more
importantly, human editable way.

The basic YAML markup has been extended to allow terse expression of
constructs that are often used in the project, such as references to
other objects.

The following is an introduction to the various structural elements of
YAML and our own extension. Note that the description for YAML are not
necessarily completely acurate. If you want the full truth about YAML,
please refer to the `specification <http://www.yaml.org/spec/>`.


YAML Structural Elements
========================

.. _base.document:

Document
--------

Each YAML file can contain multiple independent documents. Within the
project, each YAML document describes exactly one object. Thus, each file
can contain several objects.

Within a YAML file, documents are separated by three dashes on a line
by its own.


.. _base.list:

List
----

TODO


.. _base.mapping:

Mapping
-------

TODO



Value Types
===========


.. _base.data:

Date
----

TODO


.. _base.enum:

Enum
----

An enum is a string, normally consisting of a single word without any
white-space, although there is no requirement for that. For any given use
of an enum, all possibly allowed strings are well-defined in advance.


.. _base.reference:

Reference
---------

TODO
