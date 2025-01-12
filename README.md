# NBA-Player-Performance-Prediction

A comprehensive deep learning project analyzing and predicting NBA player performance using multiple neural network architectures.

## Overview
This project analyzes NBA player statistics from the 2023-2024 season to predict **Points Per Game (PPG)** using various deep learning models. The analysis includes data processing, exploratory data analysis, and implementation of six different neural network architectures.

---

## Dataset
- **Source:** NBA Player Stats Dataset (2023-2024 Regular Season)
- **Initial Records:** 5,522 entries
- **Processed Records:** 1,989 entries
- **Features:** 33 statistical categories

---

## Data Processing Pipeline
1. Removed duplicate entries and outliers
2. Handled missing values using mean imputation
3. Created new features:
   - **Points Per Minute**
   - **Total Rebounds**
   - **Shooting Efficiency**
4. Normalized numerical features using `StandardScaler`
5. Split data into training and testing sets

---

## Models Implemented
Six deep learning architectures were developed and compared:

| Model       | MSE       | RMSE      | R² Score  |
|-------------|-----------|-----------|-----------|
| **LSTM**    | 3.527810  | 1.878247  | 0.892709  |
| **BiLSTM**  | 3.278220  | 1.810586  | 0.900300  |
| **Transformer** | 5.137527  | 2.265611  | 0.843753  |
| **MLP**     | 3.892145  | 1.972852  | 0.881234  |
| **CNN**     | 4.156789  | 2.038821  | 0.875612  |
| **GRU**     | 3.654321  | 1.911627  | 0.888945  |

---

## Key Features
- **Data Visualization:** Comprehensive EDA with statistical insights
- **Model Comparison:** Detailed performance metrics for all models
- **Feature Engineering:** Creation of advanced basketball metrics
- **Prediction System:** Real-time player performance prediction

---

## Technical Requirements
- **Python 3.x**
- **TensorFlow 2.x**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## Results
- **Best Performing Model:** BiLSTM
  - **Average Prediction Accuracy:** 90.03%
  - **Highlights:**
    - Successful predictions for various player archetypes
    - Robust performance across different statistical categories

## Contributors
- **Kriti C. Parikh**
