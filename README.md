JaSpell - Java Spell Checker
============================

JaSpell is a 100% pure Java implementation of a spelling checker.  The original
version of JaSpell was developed by Bruno Martins at the XLDB group of the
Department of Informatics of the Faculty of Sciences of the University of
Lisbon in Portugal, and released in 2005 at http://jaspell.sourceforge.net/.

The library has not been updated since then, and had a few shortcomings for
people wishing to integrate it with other systems, most notably:

- its dictionary files could only be loaded from actual files on disk, not from
  other sources (e.g. bundled inside an application's JAR file)
- all text files were loaded using the platform default encoding, with no way
  to override this, meaning non-English dictionaries could not be supported in
  a cross-platform manner.

This fork fixes these problems by allowing the caller to pass in their own
`java.io.Reader` objects as an alternative to plain string file names.

As with the original JaSpell library, this version is released under a 2-clause
BSD licence.

Getting the library
-------------------

Binaries are available for download from
https://github.com/GateNLP/jaspell/releases, and release versions are available
in the Central Repository under the `uk.ac.gate` group ID

    <dependency>
      <groupId>uk.ac.gate</groupId>
      <artifactId>jaspell</artifactId>
      <version>0.3.1</version>
    </dependency>
