**Options Pricing Model**

This repository contains a Jupyter Notebook that develops an Options Pricing Model using data from the Chicago Board Options Exchange (CBOE). The project focuses on preprocessing options data, engineering features, and training a machine learning model to predict option prices based on historical trading data.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Table of Contents**
- Project Overview
- Data Sources
- Installation
- Usage
- Model and Features
- Contributing
- License
  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Overview**
This project leverages machine learning techniques to build a model that predicts options pricing. It utilizes options data from the CBOE, including daily trading volumes for the years 2021 to 2023. The model is built using a Neural Network implemented via TensorFlow/Keras, after extensive feature engineering.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Key Steps:**
- Data Loading and Merging: The notebook loads daily volume data for options trades from CSV files.
- Preprocessing: Data formatting, date handling, and moving averages are computed.
- Feature Engineering: Features such as moving averages are created from volume data to be used in modeling.
- Modeling: A sequential neural network model is built using TensorFlow/Keras to predict pricing outcomes.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Sources**


The options data used in this project comes from the Chicago Board Options Exchange (CBOE). The data includes daily volume of options trades over three years: 2021, 2022, and 2023.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Installation**
To get started, clone this repository and install the necessary dependencies.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Prerequisites**
- Python 3.x
- Jupyter Notebook

**Libraries Used**
- pandas
- scikit-learn
- tensorflow

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

You can install the required Python libraries using the following command:

`pip install -r requirements.txt`

**Usage**


**Running the Jupyter Notebook**
To use the model, simply open the Jupyter notebook and execute the cells. The notebook guides you through the data preprocessing steps, feature engineering, and model training. The data files (daily_volume_2021.csv, daily_volume_2022.csv, daily_volume_2023.csv) should be placed in the project directory.

1) **Clone the repository:**

`git clone https://github.com/your-username/options-pricing-model.git`

2) Install the necessary libraries:
   
`pip install -r requirements.txt`

4) Run the Jupyter notebook:
   
`jupyter notebook Options_Pricing_Model.ipynb`
