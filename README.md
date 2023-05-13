# Multi-Task Learning for Pun Detection and Location with BERT and Graph Convolutional Neural Networks
### SemEval-2017 Task 7
https://alt.qcri.org/semeval2017/task7/
### This is the Final Project of Group 4, COSC-572 Empirical Methods in Natural Language Processing, Spring 2023, Georgetown University
Course Webpage:\
https://people.cs.georgetown.edu/nschneid/cosc572/s23/index.html
### The Final Model is in BERT_GNN_MTL_Control_BiLSTM_v4.ipynb
https://github.com/LawrenceLLY/GNN_Pun_Detection_and_Location/blob/main/BERT_GNN_MTL_Control_BiLSTM_v4.ipynb
## The Project is Including Two Tasks:
### Subtask 1: Pun detection
For this subtask, participants are given an entire raw data set. For each context, the system must decide whether or not it contains a pun.
### Subtask 2: Pun location
For this subtask, the contexts not containing puns are removed from the data set. For each context, the system must identify which word is the pun.
## Environment:
Google Colab (with Python 3)\
https://colab.research.google.com/
## Usage:
The file name of each file contains the models which it used.\
All the files can be run in Google Colab.\
For the Evaluation.ipynb, you can load a model (.pt file) from Google Drive and do the evaluation.
## Dataset:
### 1. SemEval-2017 Task 7
https://alt.qcri.org/semeval2017/task7/data/uploads/semeval2017_task7.tar.xz
### 2. Pun of the Day
From Yang et al. (2015)\
(This dataset is not publicly available and was obtained by contacting paper authors directly.)
