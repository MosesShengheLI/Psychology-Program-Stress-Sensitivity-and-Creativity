# SPS-Stress-Sensitivity-and-Creativity_Analysis

一个基于Python的数据分析项目，旨在探究感官处理敏感性如何调节评估压力对创造力的影响。本项目复现了一项针对202名大学生的心理学实验，包含了从数据清洗、统计检验、结果可视化、探索性分析、预测性模型、简单多层感知机的完整代码。

## Project Overview
This project investigates the relationship between **Sensory Processing Sensitivity (SPS)**, **Evaluation Stress**, and **Creativity** using statistical analysis and machine learning models. The workflow is organized into five Jupyter notebooks covering data cleaning, Data analysis and visualization, exploratory analysis, predictive modeling, and a simple MLP.

---

SPS_Creativity_Project/

├─ 01_Data_Cleaning_and_EDA.ipynb

├─ 02_Statistical_Analysis.ipynb

├─ 03_Exploratory_Analysis_and_Future_Directions.ipynb

├─ 04_Predictable_Directions_in_Machine_Learning.ipynb

├─ 05_Simple_Multilayer_Perceptron.ipynb

├─ LICENSE

├─ environment.yml

├─ Raw Data.csv

├─ SPS Data.csv

└─ .gitignore

---


## Notebooks Overview

**01_Data_Cleaning_and_EDA.ipynb**  
   - Data cleaning, missing value handling, outlier detection  
   - Initial exploratory data analysis (EDA)  
   - Prepares processed datasets for downstream analysis  

**02_Statistical_Analysis.ipynb**  
   - Conducts ANOVA, ANCOVA, and other statistical tests  
   - Examines relationships between SPS, CSE, and creativity changes  
   - Generates summary tables and plots  

**03_Exploratory_Analysis_and_Future_Directions.ipynb**  
   - Additional data exploration and trend analysis  
   - Identifies features important for machine learning models  
   - Provides guidance for future predictive analysis  

**04_Predictable_Directions_in_Machine_Learning.ipynb**  
   - Implements regression models to predict creativity changes  
   - Includes feature preprocessing (one-hot encoding, scaling)  
   - Evaluates model performance on train/test splits  

**05_Simple_Multilayer_Perceptron.ipynb**  
   - Builds a simple MLP for regression using PyTorch  
   - Includes training loop, loss monitoring, and test evaluation  

---

## How to Reproduce Results

1. Clone the repository:
git clone
<https://github.com/MosesShengheLI/SPS-Stress-and-Creativity_Analysis/tree/main>

2. Set up the environment (Conda recommended):
conda env create -f environment.yml
conda activate SPS_Creativity_251001

3. Run notebooks in order:

01_Data_Cleaning_and_EDA.ipynb

02_Statistical_Analysis.ipynb

03_Exploratory_Analysis_and_Future_Directions.ipynb

04_Predictable_Directions_in_Machine_Learning.ipynb

05_Simple_Multilayer_Perceptron.ipynb

4. Replace CSV files with your own dataset if necessary.

## Notes

The included datasets are example or anonymized data. Replace with your own data as needed.

Python version _3.13_ recommended.

PyTorch CPU version is used (no CUDA required).

Visualizations use _matplotlib_ and _seaborn_.

**License**

This repository is released under the MIT License. See LICENSE for details.

**Contact**

For questions or collaboration, contact [LI Shenghe] at Mosesshengheli@163.com.
