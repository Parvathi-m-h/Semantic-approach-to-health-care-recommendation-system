# Semantic-approach-to-health-care-recommendation-system
SPARQL queries can be used to retrieve and manipulate data from the ontology repository.
Example:
To retrieve the name, age and location of the patient:
PREFIX ew:<http://www.semanticweb.org/hedathri/ontologies/2016/9/untitled-ontology-6#>
SELECT ?Patient ?age ?Location
WHERE { ?Patient ew:HasAge ?age. ?Patient ew:Haslocation?Location.}
