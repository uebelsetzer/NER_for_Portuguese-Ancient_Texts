# NER for Portuguese XVIII-Century Texts
Repository for 2nd DHandNLP paper

File "Semedo_NER_annotation.tsv" contains the final annotation of João Curvo Semedo's "Observaçoens medicas doutrinaes de cem casos gravissimos". It is a TSV file with five columns: id, original text, text after tokenisation, named entities and classes (organized as tuples of entity and tag), source file in the corpus.

The folder "gold" contains the gold standard files used to evaluate the systems' annotation. The gold standard is available both as an annotated file, with the source segment and annotated named entities, and as a glossary (a list of entities, tag, and frequency).

Paper:
```
@article{zilio2022named,
  title={Named Entity Recognition Applied to Portuguese Texts from the XVIII Century},
  author={Zilio, Leonardo and Finatto, Maria Jos{\'e} B. and Vieira, Renata},
  book={Proceedings of the Second Workshop on Digital Humanities and Natural Language Processing (2nd DHandNLP 2022)},
  pages={1--10},
  year={2022},
  publisher={CEUR}
}
```
