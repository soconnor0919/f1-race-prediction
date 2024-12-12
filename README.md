# Formula One Lap Time Prediction

## Project Overview
This project analyzes Formula One race data to predict lap times based on weather conditions, track characteristics, and other race-specific variables. Using machine learning models, we achieved significant success in predicting lap times across different tracks and conditions.

## Video Presentation

Our video presentation can be found [here](https://youtu.be/6TfnljHx6Os).

## Key Findings
- LightGBM model achieved the best overall performance (R² = 0.806, RMSE = 3.663)
- Weather conditions explain up to 80% of lap time variation
- Track-specific characteristics significantly impact model performance
- Best performance on Mexico City GP (R² = 0.899) and Belgian GP (R² = 0.845)

## Data Source
Data was obtained from the FastF1 API, which provides:

- Detailed lap timing data
- Weather conditions
- Track information
- Tire compound data
  
Link: [FastF1 Documentation](https://docs.fastf1.dev/)

## Required Packages
```yaml
dependencies:
  - python=3.10
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost
  - lightgbm
  - fastf1
  - jupyter
```

## Project Structure
- `DataPrep_EDA.ipynb`: Data preparation and exploratory analysis
- `Modeling.ipynb`: Model development and evaluation
- `Final_Report.ipynb`: Comprehensive analysis and findings
- `data/`: Directory containing cached race data
- `conda_env.yml`: Conda environment specification

## Models Used
1. LightGBM (Best performer)
2. XGBoost
3. Random Forest
4. Gradient Boosting

## Key Features
- Track temperature and air temperature interaction
- Weather complexity score
- Tire degradation metrics
- Track evolution throughout races

## Performance Metrics
Average metrics across all tracks:
```
Model               RMSE     R²    MAE
Gradient Boosting  4.259  0.726  2.083
LightGBM           3.663  0.806  1.839
Random Forest      4.915  0.644  2.396
XGBoost            4.333  0.717  2.122
```

## Setup Instructions
1. Clone the repository
2. Create conda environment:
   ```bash
   conda env create -f conda_env.yml
   ```
3. Activate environment:
   ```bash
   conda activate csci349
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

## Authors
- Sean O'Connor
- Connor Coles

## Course Information
- Course: CSCI 349 - Introduction to Data Mining
- Semester: Fall 2024
- Instructor: Brian King

## License
This project is part of academic coursework and is not licensed for commercial use.