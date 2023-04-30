# UE20CS334 - Natural Language Processing - Project

## Team 03

## Literary device Identification - Personification

### Team Members

| Name                  | SRN           |
| --------------------- | ------------- |
| Ajay Anil Kumar       | PES2UG20CS028 |
| C V Eswar Sai Reddy   | PES2UG20CS096 |
| Rudra Narayan Samanta | PES2UG20CS286 |

### Project Requirements:

Required Python Modules:

```
pandas
numpy
nltk
tensorflow
pickle
fasttext
sklearn
tqdm
regex
matplotlib
spacy
```

### Pre-Requisites

* Run below commands in terminal

  ```
  pip install -r requirements.txt
  pip install -U pip setuptools wheel
  pip install -U spacy
  python -m spacy download en_core_web_sm
  ```
* Run below commands in python shell

  ```
  import fasttext.util
  fasttext.util.download_model('en', if_exists='ignore')
  ```
* Download following files, extract them and place the GloVe embedding files in folder `word_embeddings`

  * https://nlp.stanford.edu/data/glove.6B.zip
  * https://nlp.stanford.edu/data/glove.42B.300d.zip
  * https://nlp.stanford.edu/data/glove.840B.300d.zip
  * https://nlp.stanford.edu/data/glove.twitter.27B.zip

### Main Notebooks:

There are three main Notebooks:

* main_personification_final.ipynb
* main_metaphor_final.ipynb
* main_oxymoron_final.ipynb

These files contain the implementation of detection of the respective literary device.

Open the files as Jupyter Notebook and hit `run all` at the top.

There is a `predict()` function which takes custom input and provides output from the trained models in all notebooks.
