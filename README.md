# Medical NLP in python

## Project 1: Text classification (Physical activity tweets)

### Objective: 
Given a dataset with tweets that indicate physical activities and the time when the tweet is posted, conduct a binary classification task that classifies tweets into two categories: 0 (tweeter did not engage in any physical activities) and 1 (tweeter engaged in physical activity(ies))
### Techniques used: 
- Pre-processing:
     1. Regex
     2. TF-IDF 
     3. Tokenization
     4. Stop-word removal
- Machine learning
     1. Support Vector Machine
     2. Random Forest
     3. XGBoost
     4. Ensemble methods (Stacking)
- Deep learning (transformers, [BERT](https://huggingface.co/docs/transformers/model_doc/bert), and [ELECTRA](https://huggingface.co/docs/transformers/model_doc/electra))


---

## Project 2: Named Entity Extraction (Psychiatric treatment adverse reactions)

### Objective: 
Given a dataset with reviews on the effectiveness and adverse effect of psychiatric medications (Zoloft, Lexapro, Cymbalta, and Effexor XR), train a conditional random field and deep learning model that extracts the adverse events and signs and symptoms from the setences. 
### Techniques used: 
- Machine learning: 
     - Conditional random field (pycrf)
- Deep learning: 
     - Bidirectional Long-short Term Memory (Tensorflow)
- Word embeddings (GloVe and BioWordVec)
- MetaMap 2018

---
