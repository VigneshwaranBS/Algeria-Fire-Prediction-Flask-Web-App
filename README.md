# Algeria-Fire-Prediction-Flask-Web-App

- This repository contains code for an Algeria Fire Prediction web application built using Flask. The application utilizes machine learning algorithms to predict the likelihood of forest fires in Algeria based on various environmental factors. Users can input relevant data, and the app provides a prediction of the fire risk.

## Features
Data Collection: The application collects relevant environmental data such as temperature, humidity, wind speed, and precipitation from reliable sources.
Machine Learning Model: Utilizes a trained machine learning model to predict the probability of forest fires based on the collected data.
Web Interface: Provides a user-friendly web interface where users can input the required environmental parameters for prediction.
Real-time Prediction: Generates real-time predictions by processing the user input through the machine learning model.
Visualizations: Presents the predicted fire risk and other relevant data through interactive visualizations for easy understanding.

## Getting Started
To get started with the web application, follow these steps:

Clone the repository to your local machine:
```
git clone https://github.com/your-username/algeria-fire-prediction-flask-web-app.git
```

Install the required dependencies using pip:
```
pip install -r requirements.txt
```

Run the Flask development server:
```
python app.py
```
Access the web application by visiting http://localhost:5000/predictdata in your web browser.

## Usage
- Open the web application in your browser.
- Fill in the required environmental parameters such as temperature, humidity, wind speed, and precipitation.
- Click on the "Predict" button to generate the fire risk prediction.
- The application will display the predicted fire risk along with relevant visualizations.

## Contributing
- Contributions to this project are welcome! If you'd like to contribute, please fork the repository, create a new branch for your changes, and submit a pull request. Your contributions will be reviewed by the project maintainers.

## Acknowledgements
Flask - Web framework used for developing the application.
Scikit-learn - Machine learning library used for prediction modeling.
Pandas - Data manipulation library for Python.
Matplotlib - Library for data visualization.
NumPy - Numerical computing library.
