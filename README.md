# Recursive Ekphrasis Gym

A writing assistant that shows the writer a piece of art and issues prompts designed to help the writer describe this artwork in vivid detail.

Try live version in this ☞[Google Colab Notebook](https://colab.research.google.com/drive/1w9g66oeliSMPLu9BDwVfkOIxabADk7Rr?usp=sharing)☜.  

***

This repo houses data that this notebook uses (via `wget`). 

Recursive Ekphrasis Gym makes use of `(possessor,possessed)` relations mined from Project Gutenberg:

- [`mining_gutenberg_for_relations.ipynb`](https://github.com/kbooten/ekphrasisgym/blob/main/mining_gutenberg_for_relations.ipynb) documents how I extracted `(possessor,possessed)` tuples with SpaCy
- [`processing_pairs.ipynb`](https://github.com/kbooten/ekphrasisgym/blob/main/processing_pairs.ipynb) documents some further processing of these tuples, including [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) scoring
