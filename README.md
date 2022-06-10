# Recursive Ekphrasis Gym

A writing assistant that shows the writer a piece of art and issues prompts designed to help the writer describe this artwork in vivid detail.

The interface itself exists as a ☞[Google Colab Notebook](https://colab.research.google.com/drive/1w9g66oeliSMPLu9BDwVfkOIxabADk7Rr?usp=sharing).  This repo houses data that this notebook uses (via `wget`). 

***

Recursive Ekphrasis Gym makes use of relations mined from Project Gutenberg:

- `mining_gutenberg_for_relations.ipynb` documents how I extracted `(possessor,possessed)` tuples with SpaCy
- `processing_pairs.ipynb` documents some further processing of these tuples, including tf-idf scoring
