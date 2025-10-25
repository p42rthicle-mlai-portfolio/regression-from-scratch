# Linear Regression from Scratch
This project implements **Simple Linear Regression** from scratch using **NumPy**, **Pandas**, and **Matplotlib**.  
It predicts **salary** based on **years of experience**, demonstrating how linear regression works internally without using machine learning libraries.

---

## Requirements
[numpy
pandas
numpy
jupyter]

---

## Overview
An end-to-end notebook implementing linear regression manually:
- Data exploration and visualization  
- Computation of mean, variance, normalization  
- Gradient descent optimization from scratch  
- Model training and convergence tracking  
- Final regression line and loss visualization  

---

## Dataset
Dataset: `Salary_Data.csv`  
Columns:
- `YearsExperience`: number of years of professional experience  
- `Salary`: annual salary in USD  

---

## Key Concepts

- **Linear regression equation:**  
  ŷ = wX + b  

- **Mean Squared Error (MSE):**  
  J(w, b) = (1 / 2n) * Σ (yᵢ − ŷᵢ)²  


Gradient descent for parameter updates  
Feature normalization  
Visual evaluation of regression fit and training loss  

---

## Run Locally
```bash
> clone repository

pip install -r requirements.txt
jupyter lab
```

## Screenshot
<img src="https://github.com/user-attachments/assets/3f5f7ac8-eee1-4cb1-9a28-c894958306df" alt="Notebook Screenshot" width="400" height="700">

## Results

The model successfully learns the linear mapping between years of experience and salary.
Loss decreases consistently across iterations, confirming correct implementation of gradient descent.
The regression line closely fits the data distribution

### Note
This is a learning-level project showcasing regression basics — not a production-grade work
