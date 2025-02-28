# Winstars AI DS Internship Test 2025

## 📌 Task Description


Winstars AI DS internship test 2025

The goal of this test is to evaluate your skills and knowledge in Data Science and related fields. 
We propose to solve two tasks below that contain the exercises related to Machine Learning, 
Computer Vision, NLP, and regular coding. Both tasks require skills that will be useful in the 
projects you will work on in the company. Hope it will be interesting to you. In case of any issues 
or misunderstandings - contact us. Please follow the instructions and Good Luck! 

### General requirements for the test:

● The source code should be written in Python 3.  
● The code should be clear for understanding and well-commented.  
● All solutions should be put into the GitHub repository. Each task should:  
  ○ Be in a separate folder.  
  ○ Contain its own README file with a solution explanation and details on how to set up the project.  
  ○ Have a `requirements.txt` file with all libraries used in the solution.  
● All documentation, comments, and other text information around the project should be written in English.  
● The demo should be represented as a Jupyter Notebook and contain examples of how your solution works, including descriptions of edge cases.  

---

## Task 1: Image Classification + OOP

In this task, you need to use a publicly available **MNIST dataset** and build 3 classification models:

1) **Random Forest**
2) **Feed-Forward Neural Network**
3) **Convolutional Neural Network**

Each model should be a separate class that implements `MnistClassifierInterface` with two abstract methods: `train()` and `predict()`.  
Finally, each of your three models should be hidden under another `MnistClassifier` class.  
`MnistClassifier` takes an algorithm as an input parameter.  
Possible values for the algorithm are:  
`cnn`, `rf`, and `nn` for the three models described above.

### The solution should contain:

● An interface for models called `MnistClassifierInterface`.  
● Three classes (one for each model) that implement `MnistClassifierInterface`.  
● `MnistClassifier`, which takes the algorithm name as an input parameter and provides predictions with exactly the same structure (inputs and outputs), independent of the selected algorithm.  

---

## Task 2: Named Entity Recognition + Image Classification

In this task, you will build an ML pipeline with two models performing different tasks.  
The goal is to **understand what the user is asking (NLP) and verify their statement using Computer Vision**.

### Requirements:

● Find or collect an **animal classification/detection dataset** with at least **10 animal classes**.  
● Train an **NER model** for extracting animal names from text using a **transformer-based model** (not LLM).  
● Train an **animal classification model** on your dataset.  
● Build a **pipeline** that takes a text message and an image as input.  

### Expected flow:

1. The user provides text like **"There is a cow in the picture."** and an image containing any animal.  
2. Your pipeline should **decide if the statement is true or false** and return a boolean value.  
   - The input text will **not** always be structured exactly the same way as in the example.  

### The solution should contain:

● A **Jupyter Notebook** with exploratory data analysis (EDA) of your dataset.  
● Parametrized **train and inference scripts** (`.py` files) for the **NER model**.  
● Parametrized **train and inference scripts** (`.py` files) for the **Image Classification model**.  
● A Python script for the entire **pipeline**, which takes **2 inputs** (text and image) and returns **1 boolean value**.  
