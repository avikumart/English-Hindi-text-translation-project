# English-Hindi-text-translation-project
In this repo, find the complete project to translate English to Hindi using deep neural network model.

### **🧾Description:** 
The IIT Bombay English-Hindi corpus contains parallel corpus for English-Hindi as well as monolingual Hindi corpus collected from a variety of existing sources and corpora developed at the Center for Indian Language Technology, IIT Bombay over the years. This page describes the corpus. This corpus has been used at the Workshop on Asian Language Translation Shared Task since 2016 the Hindi-to-English and English-to-Hindi languages pairs and as a pivot language pair for the Hindi-to-Japanese and Japanese-to-Hindi language pairs.

**Source of the dataset** - [Click Here](https://www.cfilt.iitb.ac.in/iitb_parallel/)

**Research paper** - [Click Here](https://arxiv.org/pdf/1710.02855.pdf)

### **🧭 Problem Statement:**
You are provided with a large dataset of language pairs, parallelly in English and Hindi: you have to perform a step-by-step NLP approach to translate English to Hindi after splitting the dataset into train-test-validation sets.


### Steps taken to solve problem

1. Load the dataset
2. Pre-processing the Hindi and English texts
3. Character level tokenization using python list and set data structures
4. Encode input and target texts using python dictionary and numpy array
5. Build the encoder and decoder architecture using LSTMs
6. Turn on GPU instance on kaggle or Colab to train model faster
7. Save the model artifact with .h5 extension
