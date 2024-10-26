# End to End Machine Learning Project

## Overview
This project provides a comprehensive machine learning pipeline to analyze student performance data, train a predictive model, and deploy it as a web application using Flask. The primary goals are to explore the data, gain insights through Exploratory Data Analysis (EDA), and develop a model that can predict outcomes based on student-related features.

## Folder Structure
- **notebook**: Jupyter notebooks for in-depth data analysis and model training.
  - **EDA STUDENT PERFORMANCE.ipynb**: Contains data exploration, visualizations, and insights.
  - **MODEL TRAINING.ipynb**: Script for model building, training, and evaluation.
- **src**: Contains core code for data preprocessing, feature engineering, and model functions.
- **templates**: HTML templates for the web interface.
- **application.py**: Main application file to run the Flask server and integrate the model.

## Setup

1. **Clone the repository** :
   ```bash
   git clone https://github.com/yourusername/MLProject.git
   cd MLProject

2. **Set up the environment** :
Create a Conda environment and install dependencies:
    ```bash
    conda create -n mlproject python=3.8
    conda activate mlproject
    pip install -r requirements.txt

4. **Run the application** :
    ```bash
    python application.py
5. **Usage** :
  Open your browser and go to http://127.0.0.1:5000 to access the application.
