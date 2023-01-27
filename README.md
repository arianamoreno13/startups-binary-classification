

Description:
This project predicts whether Alphabet Soup funding applicants will be successful, by creating a binary classification model using a deep neural network. First I Preprocess data for a neural network model. Then Use the model-fit-predict pattern to compile and evaluate a binary classification model. Then we Optimize the model by making adjustment to see if we can get a better outcome.

Installation Guide: Before running the application first install the following dependencies:

import pandas as pd
from pathlib import Path
import numpy as np
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

This project uses python 3.7 with the following packages:

[pandas] - For data analysis and manipulation.

[pathlib] - With pathlib , file paths can be represented by proper Path objects instead of plain strings as before.

[numpy] - NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. 

[tensorflow] - The TensorFlow platform helps you implement best practices for data automation, model tracking, performance monitoring, and model retraining. Using production-level tools to automate and track model training over the lifetime of a product, service, or business process is critical to success.

Usage: 
Creates deep neural networks to predict if a company will be successful after VC funding using binary classification.

Contributors: 
brought to you by ~ Ariana Moreno Linkedin-[www.linkedin.com/in/ariana-moreno-52b2b7211]

License: 
MIT