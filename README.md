# MBTI Helpdesk Ticket Classification

This repository contains the implementation and resources for the research paper **"Classifying Personality Types in Helpdesk Tickets Using Machine Learning: A Comparative Analysis of Best-Performing Models with a Multimodel Approach"**. The project focuses on classifying helpdesk tickets into Myers-Briggs personality types using machine learning techniques.

---

## Project Overview

The repository includes the following key components:

### 1. **Jupyter Notebooks**
- **01_mbti_classifiers_test.ipynb / .html**  
  Initial testing of multiple classifiers to evaluate their performance on MBTI data.
  
- **02_mbti_model_test.ipynb / .html**  
  Detailed testing and evaluation of selected models on MBTI test datasets.
  
- **03_mbti_model_tuning.ipynb / .html**  
  Hyperparameter tuning for optimizing model performance for each MBTI binary class.

- **04_mbti_model_deployment.ipynb / .html**  
  Application of tuned models for deployment on real-world helpdesk data.

### 2. **Datasets**
- **mbti_data_clean.csv.zip**  
  Training dataset for initial MBTI model development.
  
- **kaggle_servicedesk_tickets_clean.csv**  
  Cleaned helpdesk ticket dataset used for classification experiments.
  
- **kaggle_servicedesk_tickets_clean_classified.csv**  
  Labeled version of the helpdesk dataset with MBTI personality types.

---

## How to Use

1. **Setup:**  
   Clone the repository and ensure all dependencies are installed as specified in the notebooks.

2. **Run Notebooks:**  
   Use the provided `.ipynb` files for model development, testing, tuning, and deployment.

3. **Datasets:**  
   Utilize the included datasets or prepare your own according to the specified format.

4. **Deployment:**  
   Follow the steps in `04_mbti_model_deployment.ipynb` to deploy the model on real data.

---

## Research Workflow

1. **Data Preprocessing**  
   Cleaning and preparing training datasets for MBTI classification.

2. **Model Development**  
   Testing multiple classifiers and tuning the best-performing ones for each MBTI binary class.

3. **Evaluation and Deployment**  
   Applying models on real-world helpdesk data for personality prediction.

---

## Requirements

- Python 3.x
- Required libraries: (See the imports in the Jupyter notebooks for specifics)

---

## Citation

If you use this repository or the methods described in your research, please cite:  
**"Classifying Personality Types in Helpdesk Tickets Using Machine Learning: A Comparative Analysis of Best-Performing Models with a Multimodel Approach."**

---
