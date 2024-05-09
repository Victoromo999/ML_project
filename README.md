# ML Project: Predictive Maintenance

## Introduction
This project focuses on predictive maintenance using machine learning techniques. Predictive maintenance involves forecasting equipment failures before they occur, allowing for timely maintenance and reducing downtime.

## Requirements
Make sure you have the following installed:
- Python (>=3.6)
- pandas
- numpy
- tensorflow
- matplotlib
- scikit-learn

## Getting Started
1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/your-username/ML_project.git
    ```
2. Navigate to the project directory.
    ```bash
    cd ML_project
    ```
3. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Data Preparation:**
    - Place your dataset named `predictive_maintenance.csv` in the project directory.
2. **Data Preprocessing:**
    - Run `data_preprocessing.py` to preprocess the dataset and split it into train and test sets.
    ```bash
    python data_preprocessing.py
    ```
3. **Model Training:**
    - Run `model_training.py` to train a Random Forest classifier on the preprocessed data.
    ```bash
    python model_training.py
    ```
4. **Model Evaluation:**
    - The trained model's accuracy will be printed.
5. **Prediction and Failure Check:**
    - Run `failure_prediction.py` to predict failure for a specific product ID.
    ```bash
    python failure_prediction.py
    ```
6. **Visualization:**
    - Run `visualization.py` to visualize failure type distribution for each product ID.
    ```bash
    python visualization.py
    ```
7. **Reinforcement Learning:**
    - Run `reinforcement_learning.py` to train a Q-learning agent for maintenance decision-making.
    ```bash
    python reinforcement_learning.py
    ```

## Notes
- Adjust hyperparameters and settings in the respective Python files as needed.
- Ensure your dataset is appropriately formatted and contains relevant features.
- Refer to the comments within the code for further details on each step.

## References
-Bansal, S. (2021, November 6). Machine Predictive Maintenance Classification. Kaggle. https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification ​

​
