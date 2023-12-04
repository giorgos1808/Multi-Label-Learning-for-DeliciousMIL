# Learning from Data: Multi-label Classification with DeliciousMIL Dataset

## Introduction
This repository contains code and experiments related to the task of learning from data with multiple labels using the DeliciousMIL dataset. The dataset consists of a collection of documents, where each document is treated as a bag of sentences. The goal is to apply two techniques for learning from multi-label data and assess their performance.

## Dataset
The DeliciousMIL dataset is utilized in this project, comprising a set of documents where each document is represented as a bag of sentences. To process the text data, we leverage `sklearn`'s `feature_extraction.text` module, specifically using `TfidfVectorizer` for vectorization.

## Part A: Learning from Multi-label Data
In the first part of the task, we focus on learning from multi-label data. Two techniques are applied to the dataset:

1. **ClassifierChain**
   - Algorithm: LogisticRegression

2. **Ensemble Learning**
   - Algorithm: RandomForestClassifier

- Representation: Each document's representation is based on the words present in it.

## Instructions
Follow these steps to replicate the experiments:

1. **Dataset Preparation**
   - Ensure you have the DeliciousMIL dataset.
   - Organize your dataset with the specified train and test splits.

2. **Experimentation**
   - Run the provided scripts for applying ClassifierChain with LogisticRegression and RandomForestClassifier.
   - View the results and comments on the experiments.
