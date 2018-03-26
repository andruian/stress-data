# stress-data
Data for stress testing the index server

The folders [undefined](undefined),[with](with) and [without](without) contain RDF data. It was created from 
RÚIAN data using the LinkedPipes ETL tool. There are 3 entities linked to every RÚIAN ruian:AdresníMísto object.

The `with` contains buildings with an elevator. The `without` contains building without and elevator and you can 
guess what the `undefined` means.

The root folder contains data definitions to those datasets and SPARQL queries to construct the datasets.
