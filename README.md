Electrical Engineering
=====================
Hardpan Media Library - Open Book Project
-----------------------------------------

# TO DO

* Information Architecture and Appliation Usage Cases
    * Topical Ontology - `ee.rdf`
        * Overview: _Informal_ asociation of theoretical concepts within a single, concrete reference structure
        * Applications Concept: Reference ontology _Individual_ entities of type _SKOS:Concept_ for annotation of _content resources_ (articles, blogs, etc)
    * TBD:
        * Ontology of Measurements
            * Referencing Formal Public Identifiers defined originally of the so-called _HyTime_ hypermedia specification, specifically defined with regards to Systeme International (SI) _base units)
            * Referencing narrative texts published with regards to SI standards, and corresponding ISO standards, as well as of national standards agencies such as the NIST and the Royal Chemistry Society - as with regards to formal definitions of _derived units_ in so many _unit formulas_ as algebraically deriving of the SI _base units_)
            * Definint _unit formulas_ in a normative algebraic syntax - such that may very closely resemble an application of Lisp syntax, in literal text form, and may be interpreted by individual computer algebra sysetms, for any singular applications
        * Ontology of Data Types
            * IDL, the CORBA Interface Definition Langauge - with a shoutout about the design of XDR, analogously, that in a contextt of ONC RPC service definitions
            * C - Data Types; Data Values, including Primitive Values and Object Pointers; Functions; ...
            * Forth - Data Types, Data Values, Procedures, ...
            * ANSI Common Lisp - ...
            * C++ - Classes, Fields, Methods,  Templates, and Generics in a sense
            * Java - Classes, Fields, Methods, Generics
            * Unified Modeling Lagnguage (UML) _Metamodel_, as an application of  the Metaobject Framework (MOF) - MOF comprising a _Meta-Metamodel_
            * UML _Models_ as, in each, a private _application of_ the UML _Metamodel_
            * _Model Instance Data_ as in applications of user-defined UML _Models_
            * Toolchains
                * Make
                * Autoconf
                * Common Lisp Compiler
                * Java Compiler
                * Other Compiler (Ruby, Lua, Swift, PERL, PHP, Python,  ...)
                * Code-Generation Tools
                    * Modelio - UML and Java source gen; UML and C++ source gen; ...
                    * xtUML - UML and VHDL; UML and Verilog
                    * FFIGEN4
                    * IDL Compilers as _source code generation_ tools
            * Operating Systems
                * Process Activation
                * Interprocess Communications
                * Applications of Networking Standards
                * Data Serialization
                * Hardware Devices
                * Virtual Devices
                * ...
        * Ontology of Measurement Systems
            * IVI, VISA, ...
            * Interface Definitions
        * Ontology of Network Systems
            * cf. OSI seven layer model
            * TBD: PANOS IDL definitions
            * Application: Logging and reflective analysis of log data, e.g. with regards to concepts of _provenance_, in at-least assuming a concept of _data trust_
            * See also: FaceBook Engineering, [osquery](https://code.facebook.com/posts/844436395567983/introducing-osquery/)
        * Ontology of Management Tooling?

* Add licensing information - Contexts: This Document; Entire Codebase; Single Ontologies

* Integration of topical ontology with a bibliographical ontology, Zotero

* Conceptual provenance (ontology, bibliography) in definition of topical ontology

* Interpreting SKOS graph expressions - namely, _RDF Individual_ instance data and RDF data property assertions - as to create any single, visual mindmap in presentation of a data graph structured with SKOS - cf. WordNet

* Presentation of RDF _Individual_ information in and across web page resources - towards definining a web application for presentation of `ee.rdf`

* Representation in PowerLoom KIF (GraniteLoom project) - toward definitions of logical assertions stored in KIF format, onto data that mayu be structured per `ee.rdf`. Sidebar, interpreting RDF into KIF

* Representation of topical `ee.rdf` ontology concepts in DITA XML
