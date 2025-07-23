# EEG-Based Schizophrenia Classification by Susovan Patra

This repository contains the implementation of a machine learning pipeline for detecting schizophrenia using EEG data. The main focus of the project is to analyze neural patterns and build a model capable of classifying schizophrenia based on subject EEG recordings.

---

## 🔍 Key Module

> **Note:** Most of the data processing, transformation logic, and core utility functions are encapsulated in the `util` module. Please consult this module for detailed explanations of the processing workflow.

---

## 📁 Dataset Structure

The codebase assumes that all required EEG data has been manually downloaded and extracted into a local directory named `dataset`. Inside this folder, there should be individual subfolders for each of the **81 subjects**.

- [**EEG Schizophrenia Dataset – Part 1**](https://www.kaggle.com/datasets/broach/button-tone-sz)
- [**EEG Schizophrenia Dataset – Part 2**](https://www.kaggle.com/datasets/broach/buttontonesz2)

> **Important:** Due to repository size constraints, this project does **not** include raw EEG data or any model output files.

---

## 📊 Project Results

After evaluating several traditional classifiers, the **Light Gradient Boosting Machine (LGBM)** emerged as the top-performing model, outperforming other candidates with the following metrics:

- **ROC AUC Score:** 95.96%
- **Accuracy:** 90.00%

These results demonstrate the effectiveness of LGBM in distinguishing schizophrenia‑related patterns in EEG data.

---
