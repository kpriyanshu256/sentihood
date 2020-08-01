# sentihood

### Problem statement

Given a text and a target entity, we need to predict the aspects that have described in the text along with the sentiments corresponding to the aspects.

For example, given the text, "LOCATION1 is in Greater London and is a very safe place" and "LOCATION1" as target entity, the models must predict "safety" aspect with "Positive" sentiment. There maybe multiple aspects associated to a target entity.

### Approaches

1. BERT-base-uncased
2. BERT-base-uncased with Psuedo-Labelling
3. RoBERTa-base
4. RoBERTa-base with Psuedo-Labelling

### About the repository

* The dataset can be found at https://github.com/uclnlp/jack/tree/master/data/sentihood
* `src` contains the training codes
* `utils` contains some utility codes for dataset generation, submission creation etc.
* Description of the models and performance analysis of the models is present in `analysis.ipynb`
