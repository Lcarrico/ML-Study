[Home](../README.md)

# The Machine Learning Landscape

## What is Machine Learning?

- Machine Learning is creating programs that can solve problems by teaching themselves how to solve those problems through data or information.

## Why use Machine Learning?

- Machine Learning can more efficiently solve problems that have a multitude of rules by learning those rules itself, or even solve problems whose rules are not fully known. 

## Types of Machine Learning Systems

- Supervised Learning
    - The training set in supervised learning contains the labels or solutions for the data you're training with.
- Unsupervised Learning
    - In contrast with Supervised Learning, Unsupervised Learning the training data does not already contain labels or solutions and the algorithm learns without knowing the expected output. 
- Semisupervised Learning
    - Semisupervised Learning is a combination of both Supervised and Unsupervised Learning. It is where some of the training data has labels, but not all of it does. This is relatively common since a majority of real-life data tends to be unfiltered and raw. 
- Reinforcement Learning
    - Reinforcement Learning is when an algorithm learns based on positive or negative rewards given for actions done. If a series of actions lead to a positive outcome, a positive reward is given. Neutral outcomes get near zero rewards while negative outcomes receive punishment. 
- Batch Learning
    - Batch learning is when an algorithm is trained on all the availble data at once. 
    - Typically this is done with **offline learning** where the algorithm is trained while offline, and then the fully trained model is sent to production.
- Online Learning
    - With Online Learning, the algorithm is trained incrementally by feeding it data in pieces. These pieces are also known as **mini-batches**.
- Instance-Based Learning
    - Instance-Based Learning uses properties of the existing examples or data, and directly compares those to the new set of inputs. It then classifies the new inputs based on the similarities to the already existing examples. 
- Model-Based Learning
    - Model-Based Learning takes the already existing examples and generates a group of rules that form a model. The input is then sent into the model that then gives the expected output or label for that input data. 


[Example for Supervised, Model-Based Learning](first-linear-model.ipynb)

## Main Challenges of Machine Learning
- Insufficient Quantity of Training Data
- Nonrepresentitive Training Data
- Poor-Quality Data
- Irrelevant Features
- Overfitting the Training Data
- Underfitting the Training Data