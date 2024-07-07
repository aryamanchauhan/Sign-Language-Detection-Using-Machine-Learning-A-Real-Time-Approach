## Fraud Detection in E-Commerce Transactions Using Machine Learning


This repository contains the code and resources for the research paper "Sign Language Detection Using Machine Learning:
A Real-Time Approach". The project involves the development of machine learning models to detect Sign Language by individuals in real world systems.


![image](https://github.com/aryamanchauhan/Sign-Language-Detection-Using-Machine-Learning-A-Real-Time-Approach/assets/132805331/dea4613b-b73e-45d4-97c8-020fd0a6e174)


## Installation

Clone the repository : git clone https://github.com/aryamanchauhan/Sign-Language-Detection-Using-Machine-Learning-A-Real-Time-Approach

Navigate to the project directory : cd fraud-detection-ecommerce

Create and activate a virtual environment (optional but recommended) : python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install the required dependencies : pip install -r requirements.txt

## Project Structure
.gitignore: Git ignore file.

app.py: Main application script.

collectdata.py: Script to collect and preprocess data.

data.py: Script for data manipulation and preparation.

function.py: Utility functions used in the project.

model.h5: Trained model file.

model.json: Model architecture in JSON format.

trainmodel.py: Script to train the machine learning model.

## Usage

Prepare your dataset and ensure it is in the correct format as expected by the scripts.

python collectdata.py

python data.py

python trainmodel.py

python app.py
