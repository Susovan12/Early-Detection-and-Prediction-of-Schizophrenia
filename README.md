EEG-Based Schizophrenia Classification by Susovan Patra
This repository presents the source code for a machine learning project aimed at detecting schizophrenia using EEG recordings. The primary objective is to process EEG signals and build a model capable of identifying schizophrenia based on the available subject data.
🔍 Key Module

Note: The core algorithms, preprocessing routines, and analytical logic reside in the util module. For in-depth understanding of the processing pipeline, refer to the utility script, as it encapsulates the essential transformations and helper functions.


📁 Dataset Overview
The implementation expects all EEG data to be downloaded locally and placed within a root directory named dataset. Each of the 81 subjects should have their data stored in separate subdirectories within this folder.


EEG Schizophrenia Dataset – Segment 1


EEG Schizophrenia Dataset – Segment 2



Disclaimer: Due to limitations on file size, neither raw EEG data nor generated output files are included within this repository.


📊 Model Performance
Among the traditional classifiers tested, the Light Gradient Boosting Machine (LGBM) demonstrated superior performance. It achieved:


ROC AUC Score: 95.96%


Accuracy: 90%


This establishes LGBM as the most effective model in this study for distinguishing between schizophrenic and healthy EEG patterns.
