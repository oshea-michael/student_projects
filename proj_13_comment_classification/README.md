# Classification of Comments as Toxic or Non-Toxic

## Overview

Tools: Python, Pandas, NumPy, Matplotlib, scikit-learn, LightGBM, XGBoost, CatBoost, Optuna, PyTorch, BERT

Goal: Use an NLP approach to determine the toxicity of a given comment

Labeled data from a wikisite was used to train a neural network that predicts if a comment is toxic or not.

Topics/Techniques: NLP, neural networks

## Description

The goal of this project was to train a model that will classify comments as either toxic or non-toxic for moderation purposes.

The dataset includes the text of comments as well as their labels (i.e. toxic or not). The metric used to evaluate the final model was F1 score.

This task could have been approached in a variety of ways, but I decided to train a neural network using BERT to achieve the final goal. As I am new to working with neural networks, I attempted to explain the purpose of different steps in an effort to understand them better myself. Furthermore, I was unsuccessful in my first attempt to train a network, but I decided to leave the code from the first attempt at the bottom of this project.
