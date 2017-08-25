# Taxon Concept Schema extension for the Darwin Core Archive

The TDWG Taxon Concept Transfer Schema (TCS;
[github repo](https://github.com/tdwg/tcs)) is still the primary
vehicle for transferring information about details of taxon concepts
(which are taxonName plus accordingTo constructs), the relationships
among them. With the dominance of the GBIF-maintained Darwin Core
Archive (DwCA), it would be valuable to be able to express the same
inter-taxon-concept relationships in a DwCA.

This repo contains files for defining a DwCA extension for the
`TaxonRelationshipAssertion` element of TCS. Note than this element is
just part of the full TCS schema.

## Files

 * `TaxonConceptRelationship` DwCA Extension: `tcrel.xml` (During
   sandbox phase, to be placed at:
   <http://rs.gbif.org/sandbox/extension/tcrel.xml>)
 * `TaxonConceptRelationship` Ontology: `tcrel.rdf` (During sandbox
   phase, to be placed at:
   <http://rs.gbif.org/sandbox/terms/tcs/tcrel.rdf>)
 * Thesaurus/Vocab definitions: `tcreltypes.xml` (uring sandbox
   phase, to be placed at:
   <http://rs.gbif.org/sandbox/vocabulary/tcs/tcreltypes.xml>)

XSD, RNG and RNC Schema files for the `extensions` and `thesaurus` XML structures are in `schema/`.
