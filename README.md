helm-idris
==========

A Helm datasource for querying the Idris compiler

This package defines a command `helm-idris` that talks to a running Idris compiler, using its `:apropos` command to get information about queries. The first pattern is interpreted by Idris, but for the sake of speed, Helm takes care of subsequent patterns. While you search, you see semantically-colored names, type signatures, and summaries of documentation.

There are three actions: inserting the found name, inserting it fully-qualified, and looking up full documentation.
