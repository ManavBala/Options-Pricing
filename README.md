**Options Pricing Model**

This repository contains a Jupyter Notebook that develops an Options Pricing Model using data from the Chicago Board Options Exchange (CBOE). The project focuses on preprocessing options data, engineering features, and training a machine learning model to predict option prices based on historical trading data.

**Table of Contents**
- Project Overview
- Data Sources
- Installation
- Usage
- Model and Features
- Contributing
- License

**Project Overview**
This project leverages machine learning techniques to build a model that predicts options pricing. It utilizes options data from the CBOE, including daily trading volumes for the years 2021 to 2023. The model is built using a Neural Network implemented via TensorFlow/Keras, after extensive feature engineering.

**Key Steps:**
- Data Loading and Merging: The notebook loads daily volume data for options trades from CSV files.
- Preprocessing: Data formatting, date handling, and moving averages are computed.
- Feature Engineering: Features such as moving averages are created from volume data to be used in modeling.
- Modeling: A sequential neural network model is built using TensorFlow/Keras to predict pricing outcomes.
