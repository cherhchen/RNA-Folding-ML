# CS 184A Final Project: Prediction Reactivities of RNA Structures
**Group Number:**
- Canvas Group 7
- Presentation Group 12 on 12/6

**Group Members:** Cheryl Chen, Timothy Pham, Araam Abutaha

**Dataset:**
Stanford Ribonanza RNA Folding Kaggle Dataset: https://www.kaggle.com/competitions/stanford-ribonanza-rna-folding .\
Download dataset from Kaggle and put them in a `data` directory.

## Overview
Our project, RNA Folding: Predict Structures of Any RNA Molecule, focuses on the task of predicting the reactivity of RNA sequences to chemical modifiers DMS and 2A3. The significance of this relates to the scientific field with potential applications ranging from innovative drug design in medicine to various advancements in biotechnology. In the scope of computational biology, our primary challenge is to harness the capabilities of deep learning techniques, specifically Transformer and Long Short-Term Memory (LSTM) models. These models give us an insight to the complexities within RNA structures. As this report continues, we will be going over the models and their performances. Within our findings we noticed that both LSTM and transformer models turned out to be good at handling RNA sequences. One noticeable difference is that the transformer model performed better. This is mainly because of the transformer model’s use of self-attention and multihead-attention mechanisms. These mechanisms help the model figure out and give weight to different parts of RNA sequences more effectively.

## Software Used
| Purpose             | Software |
| :---------------- | :------: |
| Data exploration, cleaning, and visualization      |   Pandas, Matplotlib, NumPy   |
| Model training         |   Tensorflow, Keras, scikit-learn  |

Register for a Kaggle account and download the dataset listed above before running the project.

## LSTM Model
The LSTM model can be found in the notebook `lstm_model.ipynb`. NumPy, Pandas, Matplotlib, scikit-learn, Tensorflow, and Keras are used. 

## Transformer Model
The Transformer model can be found in the notebook `transformer_model.ipynb`. NumPy, Pandas, Matplotlib, scikit-learn, Tensorflow, Keras, and Keras-NLP are used.
