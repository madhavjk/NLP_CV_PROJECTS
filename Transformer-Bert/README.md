# Transformers for Natural Language Processing

![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![NLTK](https://img.shields.io/badge/Library-nltk-orange.svg)

![NLP][image](https://user-images.githubusercontent.com/42112240/132096246-13fa0cfd-b141-4a07-8628-50388703d2b2.png)


This is the code repository for Transformers for Natural Language Processing Projects. 



## Description:
Transformers for Natural Language Processing investigates in vast detail the deep learning for machine translations, speech-to-text, text-to-speech, language modeling, question answering, and many more NLP domains in context with the Transformers.

The repo takes you through Natural language processing with Python and examines various eminent models and datasets in the transformer technology created by pioneers such as Google, Facebook, Microsoft, OpenAI, Hugging Face, and other contributors.

Firstly, I worked with transformer architectures, starting with the original Transformer, before moving on to RoBERTa, BERT, and DistilBERT models. And, I learnt to train methods for smaller Transformers that can outperform GPT-3 in some cases. Secondly, I applied Transformers for Natural Language Understanding (NLU) and Generation. Finally, we  advanced language understanding techniques such as optimizing social network datasets and fake news identification.

By the end, we will understand transformers from a cognitive science perspective and be proficient in applying pre-trained transformer models by tech giants to various datasets.

## Things I learnt during:
* Use the latest pretrained transformer models
* Grasp the workings of the original Transformer, GPT-2, BERT, T5, and other transformer models
* Create language understanding Python programs using concepts that outperform classical deep learning models
* Use a variety of NLP platforms, including Hugging Face, Trax, and AllenNLP
* Apply Python, TensorFlow, and Keras programs to sentiment analysis, text summarization, speech recognition, machine translations, and more
* Measure the productivity of key transformers to define their scope, potential, and limits in production

The code will look like the following:
```python
#@title Activating the GPU
# Main menu->Runtime->Change Runtime Type
import tensorflow as tf
device_name = tf.test.gpu_device_name()
if device_name != ‘/device:GPU:0’:
  raise SystemError(‘GPU device not found’)
print(‘Found GPU at: {}’.format(device_name))
```




