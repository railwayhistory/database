:path: ref/line/concession
:lang: en
:title: The 'concession' Line Event Attribute

The *concession* Line Event Attribute
=====================================

The concession is the right to build and operate a railway granted to
a company by the local authorities. In a wider sense, we use this
attribute to describe the legal grounds on which construction and
operation of a railway line are based.

The value of the *concession* attribute is a
:ref:`~base.mapping` containing three optional keys:

The key *by*, if present, shall contain a
:ref:`~base.reference` to the
:ref:`organization` that granted the concession.

The key *for*, if present, shall contain a
:ref:`~base.reference` to the
:ref:`organization` that is the beneficiary of
the concession.

The key *until*, if present, shall contain a
:ref:`~base.date` specifying when the concession will
expire unless further action is taken.

The key *document*, if present, contains a
:ref:`~base.reference` to the
:ref:`source` for the document that contains the concession.
