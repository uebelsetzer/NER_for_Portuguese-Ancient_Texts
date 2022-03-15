# NER for Portuguese XVIII-Century Texts
Repository for 2nd DHandNLP paper

File "Semedo_NER_annotation.tsv" contains the final annotation of João Curvo Semedo's "Observaçoens medicas doutrinaes de cem casos gravissimos". It is a TSV file with five columns: id, original text, text after annotated (space-separated tokens), named entities and classes (organized as tuples of entity and tag), source file in the corpus.

The folder "gold" contains the gold standard files used to evaluate the systems' annotation. The gold standard is available both as an annotated file, with the source segment and annotated named entities, and as a glossary (a list of entities, tag, and frequency).
