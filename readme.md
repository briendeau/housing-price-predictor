# 🏡 Boston Housing Price Prediction

Predicting housing prices in Boston using machine learning techniques.

![Project Banner](https://upload.wikimedia.org/wikipedia/commons/5/5f/Boston_MA_Skyline.jpg)

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🧠 Overview

This project aims to predict the median value of owner-occupied homes in Boston suburbs using various features such as crime rate, average number of rooms, and accessibility to highways. We employ multiple regression techniques and evaluate their performance.

## 📊 Dataset

The [Boston Housing Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#boston-house-prices-dataset) contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It has 506 instances with 13 features.

**Features:**

- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centres
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population

**Target:**

- MEDV: Median value of owner-occupied homes in $1000's

  

## 📈 Results

The final model achieved the following performance:

- **Root Mean Squared Error (RMSE):** 0.12
- **R² Score:** 0.92

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ames-housing-price-prediction.git
   cd ames-housing-price-prediction
   ```

📁 Data
The dataset used is the Ames Housing dataset, which includes 79 explanatory variables describing (almost) every aspect of residential homes

📚 References
Kaggle: House Prices - Advanced Regression Techniques

Ames Housing dataset documentation

👤 Author
Your Name - your.email@example.com

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

