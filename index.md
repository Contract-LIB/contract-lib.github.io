---
layout: default
title: Main Page
---

# About Contract-LIB

Contract-LIB is a language that allows to declare abstractions and define contracts based on them in an abstract way independently of the concrete programming language. It builds on SMT-LIB and adds two new commands `declare-abstractions` and `define-contract`.

Contract-LIB is not intended to be written directly by humans. Instead, we provide various tools to translate from and to different front-end languages, such as the Java Modeling Language (JML), Dafny, and VeriFast.

Currently, we the following tools are available:
* An ANTLR4 grammar based on the SMT-LIB grammar (version 2.6), and tools traversing the AST, creating nodes, ... (for implementing custom importers/exporters).
* Various tools for exporting to or importing from front-end languages:
    * Contract-LIB to the Java Modeling Language (JML)
    * Contract-LIB to VeriFast
    * ...

# Publications
For more information, we refer to our ISoLa 2024 paper: <https://doi.org/10.1007/978-3-031-75380-0_6>
