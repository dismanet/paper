## Disease Vocabularies

For each disease vocabulary in DisMaNET, a TSV file is provided with the following columns:

* ID (Required): The unique ID of the disease term in the vocabulary.
* NAME (Required): The name of the disease term in the vocabulary.
* PARENT_ID/DESCRIPTOR_ID (Optional): If the vocabulary has a hierachical structure, this column contains the ID of the parent element. The DESCRIPTOR_ID applies only for the MeSH SCRs, and contains the ID of the associated MeSH descriptor.
* LEVEL (Optional): The depth of the term in the hierarchical vocabulary, with respect to the root.
* ROOT_CATEGORY (Optional): The name of the top-level category in the hierarchy
* PARENT_CATEGORY (Optional): Applies only to MeSH, where descriptors have multiple parents described by the tree category.

## Disease Vocabulary Cross-Mappings

When a mapping between terms of two vocabularies exists, a TSV file with the name format source_to_target is provided with the following columns:

* ID (Required): The unique ID of the disease term in the source vocabulary.
* MAP_ID (Required): The unique ID of the disease term in the target vocabulary.
* NAME (Optional): The name of the disease term in the source vocabulary.
* MAP_NAME (Optional): The name of the disease term in the target vocabulary
