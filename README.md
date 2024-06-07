### Industrial Copper Modeling

## Project Structure

The project consists of the following files and directories:
data/: Directory containing the raw data file(s) for the industrial copper dataset.
modeling.ipynb: Jupyter Notebook file containing the code for building regression and classification models.
pickle_file_generator.ipynb: Jupyter Notebook file for generating the pickle file of the trained model.
streamlit_app.py: Python file containing the Streamlit application code for using the trained model to predict selling price and status.

## Prerequisites

Before running the code, ensure that you have the following dependencies installed:
- Python (version 3.7 or above)
- Pandas
- Numpy
- Scikit-learn
- Streamlit

In this project, we have successfully developed a pipeline to preprocess industrial copper data, handle missing values, detect outliers, and address skewness. We have also built regression and classification models to predict the selling price and determine if a sale was won or lost. The trained models have been saved as a pickle file for easy retrieval. The Streamlit application provides a user-friendly interface to utilize the trained model for making predictions.
