# Named entity recognition (NER) in spaCy
29 May 2020
  
Check out the [NER in spaCy notebook!](https://nbviewer.jupyter.org/github/kriesbeck/spacy-ner/blob/master/NER%20in%20spaCy.ipynb "NER in spaCy")

The 'NER in spaCY' notebook reviews named entity recognition (NER) in spaCy using:
* Pretrained spaCy models
* Customized NER with:
 * Rule-based matching with EntityRuler
   * Phrase matcher
   * Token matcher
 * Custom trained models
   * New model
   * Updating a pretrained model

## Setup

There is a requirements.txt file in this repository.

To setup:
1. clone the repository
2. cd to the directory where requirements.txt is located
3. activate your virtualenv
4. run: pip install -r requirements.txt

## Resources

https://www.youtube.com/watch?v=sqDHBH9IjRU  
https://spacy.io/api/entityruler#add_patterns  
https://spacy.io/api/annotation#named-entities  
https://explosion.ai/blog/pseudo-rehearsal-catastrophic-forgetting  
https://spacy.io/usage/training  
https://github.com/explosion/spaCy/blob/master/examples/training/train_ner.py  
https://spacy.io/usage/training#tips-batch-size  
https://aihub.cloud.google.com/p/products%2F2290fc65-0041-4c87-a898-0289f59aa8ba  