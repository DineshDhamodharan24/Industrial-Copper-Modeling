# Industrial-Copper-Modeling

This project centers around modeling industrial copper data using Python, leveraging essential libraries such as pandas, numpy, and scikit-learn. The primary goal is to preprocess the data by handling missing values, detecting outliers, and addressing skewness. Subsequently, both regression and classification models will be constructed to predict the selling price and determine the outcome of a sale (won or lost). The trained models will be saved as a pickle file for future integration into a Streamlit application.

**HOMEPAGE**
![image](https://github.com/DineshDhamodharan24/Industrial-Copper-Modeling/assets/142207421/0c795790-2374-424b-9b68-4bc234a4310e)

**PRICE PREDICTION**
![image](https://github.com/DineshDhamodharan24/Industrial-Copper-Modeling/assets/142207421/f3efb562-694d-4ab0-a242-ddacc8e1a8c4)

**PREDICT STATUS**
![image](https://github.com/DineshDhamodharan24/Industrial-Copper-Modeling/assets/142207421/e0e496ba-f42f-48d0-824e-352a45be8b7a)

**PROJECT STRUCTURE**

data/: This directory contains the raw data file(s) for the industrial copper dataset.

modeling.ipynb: A Jupyter Notebook file containing the code for constructing regression and classification models.

pickle_file_generator.ipynb: Another Jupyter Notebook file dedicated to generating the pickle file that stores the trained model.

streamlit_app.py: This Python file houses the code for the Streamlit application. It utilizes the trained model to predict the selling price and determine the status of a sale

**PREREQUISITES**

Before running the code, ensure that you have the following dependencies installed:

*Python 
*Pandas
*Numpy
*Scikit-learn
*Streamlit

In this project, we have successfully developed a pipeline to preprocess industrial copper data, handle missing values, detect outliers, and address skewness. We have also built regression and classification models to predict the selling price and determine if a sale was won or lost. The trained models have been saved as a pickle file for easy retrieval. The Streamlit application provides a user-friendly interface to utilize the trained model for making predictions.
