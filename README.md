# LinkedData_KParker
Linked Data project for University of Alabama master's degree project, LS 563.

A. dataset description
  This dataset contains data about the first 4 rounds of the UEFA Champions League season, 2025-2026.
  
B. ontology(ies) and controlled vocabularies used
  IPTC, sportsschema.org, is the primary ontology used.
  Wikidata was used for identification of individuals.
  Geonames was used to identify the stadium locations.
  
C. linking strategy
  The sports ontologies were lacking in the complete vocabulary necessary for linking so common public ontologies were substituted to compensate for the lack of time available to adjust the sportsschema.org ontology.
  
D. sample triples:
  
WD:Q13511583  rdf:type  foaf:Person .

schema:EintFrankfurt  rdf:type  rdf:Property .

WD:Q4453759  rdf:type  foaf:Person .

schema:Liverpool  rdf:type  rdf:Property .

WD:Q55074091  rdf:type  vcard:Location .
