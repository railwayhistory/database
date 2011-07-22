:path: ref/line/contract
:lang: en
:title: The 'contract' Line Attribute

The *contract* Line Attribute
=============================

The *contract* line attribute indicates that a contract has been
concluded on the date of the event regarding this line.  The term
contract is to be considered in a wider sense as any form of agreement
between two or more parties. Thus, it also contains treaties between
countries.

The value of the *contract* attribute is a :ref:`~base.mapping`
containing two optional key:

The key *partners*, if present, contains a :ref:`~base.list` of
:ref:`references <~base.reference>` to the
:ref:`organizations <organization>` participating in the contract.

The key *document*, if present, contains a :ref:`~base.reference` to the
:ref:`source` for the particular contract.
