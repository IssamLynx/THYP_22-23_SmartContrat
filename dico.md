@prefix rdfs:	<http://www.w3.org/2000/01/rdf-schema#> .
@prefix dbo:	<http://dbpedia.org/ontology/> .
dbo:popularVote	rdfs:domain	dbo:Election .
@prefix rdf:	<http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix owl:	<http://www.w3.org/2002/07/owl#> .
dbo:Election	rdf:type	owl:Class ;
	rdfs:subClassOf	dbo:SocietalEvent .
@prefix wikidata:	<http://www.wikidata.org/entity/> .
dbo:Election	owl:equivalentClass	wikidata:Q40231 ;
	rdfs:label	"toghch\u00E1n"@ga ,
		"\u03B5\u03BA\u03BB\u03BF\u03B3\u03AE"@el ,
		"verkiezing"@nl ,
		"elezione"@it ,
		"\u00E9lection"@fr ,
		"Election"@en ,
		"Wahl"@de ,
		"\uC120\uAC70"@ko ,
		"elecci\u00F3n"@es ,
		"\u0627\u0646\u062A\u062E\u0627\u0628\u0627\u062A"@ur ,
		"\u9078\u6319"@ja ;
	rdfs:isDefinedBy	dbo: .
@prefix wdrs:	<http://www.w3.org/2007/05/powder-s#> .
dbo:Election	wdrs:describedby	<http://dbpedia.org/ontology/data/definitions.ttl> ;
	owl:sameAs	dbo:Election .
@prefix prov:	<http://www.w3.org/ns/prov#> .
@prefix ns7:	<http://mappings.dbpedia.org/index.php/OntologyClass:> .
dbo:Election	prov:wasDerivedFrom	ns7:Election .
@prefix ov:	<http://open.vocab.org/terms/> .
dbo:	ov:defines	dbo:Election .
<http://dbpedia.org/ontology/data/definitions.ttl>	ov:describes	dbo:Election .
