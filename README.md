# Waste Data in Israel

This project analyzes and predicts waste disposal patterns in various cities across Israel. By leveraging demographic, infrastructural, and environmental data, the project aims to identify key factors influencing public waste disposal behavior and provide actionable insights for improving urban waste management.

## Description

The primary goal of this project is to predict and analyze waste disposal patterns in Israeli cities. The project uses various statistical models such as Linear Regression, Random Forest, XGBoost and Ggradient Boosting to analyze a comprehensive dataset that includes demographic information, infrastructural data, and environmental factors. By understanding these patterns, we aim to help municipalities and waste management companies optimize their strategies and reduce public waste more effectively.

## Data Preparation

Data for this project was collected from several governmental and public sources. The preparation process includes:

1. **Data Collection:** Gathering data on population demographics, waste management infrastructure, environmental conditions, and more.
2. **Data Cleaning:** Handling missing values, normalizing data, and combining datasets to create a unified structure.
3. **Feature Engineering:** Creating new features that might improve model performance, such as combining related variables or creating ratios.
4. **Data Splitting:** Splitting the dataset into training and testing sets to evaluate model performance.

The processed data is then used to train various predictive models, helping to identify significant patterns and influences.

## Results

The analysis uncovered significant differences in waste disposal patterns across different cities and population groups. The more advanced models, such as Random Forest and XGBoost, provided better predictive accuracy than simpler models like Linear Regression. These results can help urban planners and waste management authorities target areas that require more effective waste management solutions.

## How to Run (in Google Colab)

You can run this project directly in Google Colab by following these steps:

1. **Open Google Colab** and ensure you are logged into your Google account.
2. **Upload the Notebook**: Upload the `data_waste_israel.ipynb` file to Google Colab.
3. **Install Dependencies**: Run the following command in a cell to install any required libraries:

    ```python
    !pip install -r requirements.txt
    ```

4. **Run the Notebook**: Execute the cells in the notebook sequentially. The notebook includes detailed comments and instructions to guide you through the data preparation, modeling, and analysis processes.

5. **View Results**: After running the notebook, you will be able to see the results of the models, including visualizations and performance metrics.

This project can also be cloned and run locally if you prefer. Just ensure that you have all the necessary dependencies installed.

---

