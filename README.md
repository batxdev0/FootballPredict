# FootballPredict

A Premier League match outcome predictor using scikit-learn and match statistics from 2020-2022.

## Overview
This project uses a Random Forest Classifier to predict match outcomes (win/loss) based on historical match data. The data is sourced from `matches.csv`, which contains detailed statistics for each match.

## Features
- Predicts match outcomes using machine learning
- Utilizes rolling averages of key statistics for improved accuracy
- Supports analysis by team and opponent

## Setup
1. Clone the repository and navigate to the project directory.
2. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas scikit-learn
   ```
4. Ensure `matches.csv` is present in the project directory.

## Usage
Run the predictor script:
```bash
python main.py
```

## Output
- Prints prediction accuracy and precision
- Generates a merged DataFrame with actual and predicted results

## Author
Batu Taskan 