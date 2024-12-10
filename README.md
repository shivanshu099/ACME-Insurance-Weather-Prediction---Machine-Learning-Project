# ACME Insurance & Weather Prediction - Machine Learning Project

This repository contains machine learning models built to solve two distinct real-world problems using decision tree algorithms. The primary focus is on predicting:

1. **Annual Medical Expenditure** for new customers of ACME Insurance Inc.
2. **Rain Prediction** for various locations across Australia based on historical weather data.

## Table of Contents
- [Problem 1: Medical Expenditure Estimation](#problem-1-medical-expenditure-estimation)
- [Problem 2: Rain Prediction](#problem-2-rain-prediction)
- [Modeling Approach](#modeling-approach)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

---

## Problem 1: Medical Expenditure Estimation

**Context:**
ACME Insurance Inc. provides affordable health insurance to customers across the United States. As the lead data scientist at ACME, you are tasked with creating a predictive system to estimate the annual medical expenditure of new customers based on certain features such as:
- **Age**
- **Sex**
- **BMI (Body Mass Index)**
- **Number of children**
- **Smoking habits**
- **Region of residence**

The goal is to develop an automated system using machine learning models to predict the annual medical expenditure for new customers.

**Dataset:**
The dataset includes customer details and their medical expenses. Each record in the dataset corresponds to a customer, and the goal is to predict their medical expenditure.

---

## Problem 2: Rain Prediction

**Context:**
The **Rain in Australia** dataset contains daily weather observations over 10 years from various Australian weather stations. As a data scientist at the Bureau of Meteorology, your task is to create an automated system to predict whether it will rain tomorrow, based on the current day's weather data.

**Dataset:**
The dataset contains various weather-related features such as:
- Temperature
- Humidity
- Wind speed
- Rainfall, etc.

Using these features, the model predicts whether rain will occur tomorrow at a specific location.

---

## Modeling Approach

For both problems, a **Decision Tree Classifier** is used as the core machine learning model. Decision Trees are chosen for their simplicity, interpretability, and ability to handle both categorical and continuous data.

- **Problem 1 (Medical Expenditure Estimation)**: We treat this as a **regression problem** where the target variable is continuous (annual medical expenditure).
- **Problem 2 (Rain Prediction)**: This is framed as a **classification problem** where the target variable is binary (will it rain tomorrow: Yes/No).

---

## Installation

To get started with this project, clone the repository and install the necessary dependencies.

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ml-project.git
   cd ml-project
##--------------------------------------------------##
