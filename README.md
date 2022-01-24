<p align="center"><img src="./imgs/plod.png" alt="logo" width="50" height="84"/></p>

# PLOD: An Abbreviation Detection Dataset  
[![GitHub issues](https://img.shields.io/github/issues/surrey-nlp/PLOD-AbbreviationDetection?style=flat-square)](https://github.com/surrey-nlp/PLOD-AbbreviationDetection/issues)
[![GitHub stars](https://img.shields.io/github/stars/surrey-nlp/PLOD-AbbreviationDetection?style=flat-square)](https://github.com/surrey-nlp/PLOD-AbbreviationDetection/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/surrey-nlp/PLOD-AbbreviationDetection?style=flat-square)](https://github.com/surrey-nlp/PLOD-AbbreviationDetection/network)
[![GitHub license](https://img.shields.io/github/license/surrey-nlp/PLOD-AbbreviationDetection?style=flat-square)](https://github.com/surrey-nlp/PLOD-AbbreviationDetection)
[![Twitter](https://img.shields.io/twitter/url?style=flat-square&url=https%3A%2F%2Fgithub.com%2Fsurrey-nlp%2FPLOD-AbbreviationDetection)](https://twitter.com/intent/tweet?text=AbbreviationDetectionDataset:&url=https%3A%2F%2Fgithub.com%2Fsurrey-nlp%2FPLOD-AbbreviationDetection)

This is the repository for PLOD Dataset submitted to LREC 2022. The dataset can help build sequence labelling models for the task Abbreviation Detection. 
### Dataset
The dataset is present [here at this link](https://drive.google.com/drive/folders/1uI6V8-A1uoB05fUC2znrQLvHouMqUusK?usp=sharing).<br/>

### Installation
We use the custom NER pipeline in the [spaCy transformers](https://spacy.io/universe/project/spacy-transformers) library to train our models. This library supports training via any pre-trained language models available at the [HuggingFace repository](https://huggingface.co/).<br/>
Please see the instructions at these websites to setup your own custom training with our dataset.

### Model
The working model is present [here at this link](https://huggingface.co/surrey-nlp/en_abbreviation_detection_roberta_lar).<br/>
On the link provided above, the model can be used with the help of the Inference API via the web-browser itself. We have placed some examples with the API for testing.<br/>

#### Usage (in Python)
You can use the HuggingFace Model link above to find the instructions for using this model in Python locally. 





