# Decision Tree from Scratch 🌳

This repository contains a step-by-step implementation of a **Decision Tree Classifier** built entirely from scratch using **Python**.  
The goal of this project is to understand the internal working of Decision Trees — from calculating entropy and information gain to splitting data and making predictions — without relying on any pre-built machine learning libraries.

---

## 📘 Overview
A Decision Tree is a supervised machine learning algorithm used for both **classification and regression** tasks.  
This project walks through the complete process of building a **Decision Tree Classifier**, focusing on the math and logic behind it.

---

## 📂 Dataset
The implementation uses a **simple sample dataset** to demonstrate the working of the Decision Tree.  
The dataset includes features and labels designed to help visualize how the tree splits data based on **information gain**.  
It can easily be replaced or expanded with other datasets such as:
- The classic **Iris dataset**
- **Play Tennis dataset**
- Any custom CSV file with categorical/numerical attributes

---

## 🌲 Type of Decision Tree Implemented
- **Algorithm Type:** Classification Tree  
- **Splitting Criterion:** Entropy / Information Gain  
- **Implementation:** Pure Python (no Scikit-learn or external ML frameworks)  
- **Approach:** Recursive tree-building to determine the best feature split at each node

---

## 📊 Results
The final Decision Tree successfully:
- Classifies samples based on learned splits  
- Prints the structure of the built tree in a readable format  
- Shows how information gain guides the split decisions  
- Demonstrates prediction accuracy on test examples

## 🚀 Future Improvements
Potential next steps to enhance this project:
- Implement **Gini Index** as an alternative splitting criterion  
- Extend to **Regression Trees**  
- Add **Tree Visualization** using Graphviz or Matplotlib  
- Handle **continuous attributes** and automatic threshold selection  
- Compare performance with `scikit-learn`’s DecisionTreeClassifier

---

## 🧠 Learning Outcome
This project helps in:
- Understanding the mathematical foundation of Decision Trees  
- Learning how entropy and information gain drive decision-making  
- Strengthening Python coding and logical thinking skills  
- Building confidence to implement other ML algorithms from scratch  

---
