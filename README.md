# Predicting Thermodynamic Properties Using Random Forest

This repository contains code and data for predicting thermodynamic properties such as density (**ρ**), specific heat capacities at constant pressure (**C**<sub>p</sub>) and volume (**C**<sub>v</sub>), volume expansion coefficient (**γ**), linear expansion coefficient (**α**), and bulk modulus (**K**) using Random Forest (RF) models. The predictions utilize descriptors calculated from PaDEL-Descriptor software and focus on identifying the most important features influencing these properties.

## Overview

The project is divided into two main tasks:

1. **Single-task Random Forest (RF)**: 
   - Predicts **ρ**, **C**<sub>p</sub>, **C**<sub>v</sub>, **γ**, **α**, and **K** using RF models.
   - Analyzes the predictive capability of the models for density and specific heat capacities.

2. **Multitask Random Forest (RF)**: 
   - Provides predictions for **ρ**, **C**<sub>p</sub>, **C**<sub>v</sub>, **γ**, **α**, and **K**.
   - Evaluates the performance of the models using all descriptors and highlights the importance of selected features.

## Features

- **Data Processing**: 
  - Prepares the dataset with necessary descriptors.
  
- **Model Training**: 
  - Implements RF for both single-task and multitask predictions.
  
- **Feature Importance**: 
  - Identifies top important descriptors for each property.

- **Graphical Representation**: 
  - Provides visualizations for better understanding of predictions and relationships between properties.

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn


