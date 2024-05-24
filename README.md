# Iris Dataset Analysis and Visualization

## Introduction

This project involves the analysis and visualization of the Iris dataset. The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains 150 samples of iris flowers, with four features (sepal length, sepal width, petal length, and petal width) and a target variable representing the species of the iris flower (setosa, versicolor, and virginica).

## Steps Involved

1. **Loading the Dataset**:
   - Import necessary libraries
   - Load the Iris dataset into a Pandas DataFrame

2. **Data Exploration**:
   - View the first few rows of the dataset
   - Generate summary statistics
   - Check for missing values

3. **Data Visualization**:
   - Create pair plots to visualize pairwise relationships
   - Plot histograms to see the distribution of features
   - Generate box plots to visualize the spread of features
   - Create a heatmap to show the correlation matrix

4. **Feature Analysis**:
   - Scatter plots to see relationships between specific features
   - KDE plots for density estimation

5. **Model Training (Optional)**:
   - Split data into training and testing sets
   - Train a simple machine learning model (e.g., Logistic Regression)
   - Evaluate the model using classification report and confusion matrix

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/imvanshika/IrisdatasetAnalysis.git

2. Navigate to the project directory:
   ```bash
   cd irisAnalysis

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Run the analysis script:
   ```bash
   python analysis.py
