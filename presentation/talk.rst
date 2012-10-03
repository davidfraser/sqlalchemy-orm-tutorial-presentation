Introduction to SQLAlchemy
+++++++++++++++++++++++++++++

* How to use SQLAlchemy
* Primarily as an ORM layer
* But also explaining the other parts

Introduction
============

* Relational databases
* Python DBAPI
* ORM layers

Philosophy of SQLalchemy
========================

* Abstraction (leaky)
* Database Independence
* But Hand-Coded

SQLalchemy core
===============

* Engines and connections
* Data Types
* Schema Definition
* SQL expressions

Engines and connections
=======================

* What a database URL is
* Step 1 - connecting to SQLalchemy and running a simple statement

Data Types
==========

Schema Definition
=================

SQL expressions
===============

ORM Tutorial (using ``declarative``)
====================================

* Basics
* Querying
* Relationships
* Eagerness
* Deleting
* Bonus Round

Basics
======

* will actually work through the standard tutorial from the documentation
* Step 2 - importing declarative and setting up a table
* Creating records, adding and simple querying
* record statuses, flushing and committing
* rollback

Querying
========

* Querying - record objects, named tuples
* Aliases
* Filtering
* Ordering, selecting ranges, first/one/all
* Literal SQL
* Counting

Relationships
=============

* Declaring relationships with foreign keys
* Working with related records
* Querying with joins
* Table aliases

**TODO** below here

* Subqueries and mapping to entities
* exists, has, any
* Relationship operators

The importance of being eager
=============================

* Eager loading
* joined load

Deleting
========

* Deleting
* Cascading

Bonus Round
===========

* Many to many relationships

Sessions and Concurrency
========================

* some tips

