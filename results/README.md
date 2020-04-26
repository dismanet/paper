## Result Datasets

These files contain the mappings found with DisMaNET for MeSH, DisGeNET, MonDO and DISNET. 

* id (Required): The unique ID of the disease term in the origin vocabulary.
  * MeSH: MeSH ID
  * DisGeNET: CUI
  * MonDO: MonDO ID
  * DISNET: DISNET ID
* name (Required): The name of the disease term in the origin vocabulary.
* resource_id (Required): The ID of the target vocabulary, following the conventions of the origin vocabulary.
* distance (Required): The distance between the origin and target terms in the DisMaNET graph.
* similarity (Required): The Cosine Similarity of the origin and target terms.
* score (Required): The computed DisMaNET relevance score of the mapping.
* url (DISNET only): The url of the disease article associated to the DISNET term.
