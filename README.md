# Diabetes Prediction Web App

This is a simple web application built with Flask for predicting diabetes based on user input.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Files and Directory Structure](#files-and-directory-structure)
- [Contributing](#contributing)
- [License](#license)

## Description

This web application uses a machine learning model to predict whether a person is diabetic or non-diabetic based on input features such as Glucose, Blood Pressure, BMI, etc.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/diabetes-prediction-web-app.git

A. Change into the project directory:
   cd diabetes-prediction-web-app

B. Install the required dependencies:
   pip install -r requirements.txt

## Usage for Local Machine

1. Run the Flask application:
   python app.py

2. Open your web browser and go to http://localhost:5000 to access the web app.

3. Enter the required information, and the application will predict whether the person is diabetic or non-diabetic.

## Dependencies:

1. Flask
2. NumPy
3. pandas
4. scikit-learn

## Files and Directory Structure:

app.py: The main Flask application file.

Model/standardScalar.pkl: Pickle file containing the standard scaler for feature scaling.

Model/modelForPrediction.pkl: Pickle file containing the trained machine learning model.

templates/: Folder containing HTML templates for the web pages.

## Contributing: 

Feel free to contribute by opening issues or submitting pull requests. Follow the Contributing Guidelines for more details.

## License:

This project is licensed under the MIT License.