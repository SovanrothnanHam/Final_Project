# Diseases Prediction Using Machine Learning with Flask App 

### Machine Learning Model Deployment with Flask

This repository contains a Flask web application for deploying machine learning models to predict heart disease and diabetes based on user input.

### Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Python 3
- Flask
- NumPy
- pandas
- scikit-learn (sklearn)


### Usage

1. **Clone the Repository**

   Clone this repository to your local machine

2. **Run the Flask Application**

   Execute the following command to run the Flask application:

   ```bash
   python app.py
   ```

   The application will start running on `http://localhost:5000/`.

### Project Structure

- **`app.py`**: Contains the Flask application code for defining routes and handling model predictions.
  
- **`heart.pkl`**: Pre-trained machine learning model (pickle file) for predicting heart disease.

- **`diabetes.pkl`**: Pre-trained machine learning model (pickle file) for predicting diabetes.

- **`templates`**:
  - **`home.html`**: HTML template for the home page.
  - **`heartdisease.html`**: HTML template for displaying heart disease prediction results.
  - **`diabetes.html`**: HTML template for displaying diabetes prediction results.

### Routes

- **`/`**: Home page that renders `home.html`.
- **`/heartdisease/`**: Route for heart disease prediction.
- **`/predictheartdisease/`**: Endpoint for predicting heart disease based on user input.
- **`/diabetes/`**: Route for diabetes prediction.
- **`/predictdiabetes/`**: Endpoint for predicting diabetes based on user input.

### Predictions

- **Heart Disease Prediction**:
  - Access the heart disease prediction page at `/heartdisease/`.
  - Submit form data to `/predictheartdisease/` to get the prediction result.

- **Diabetes Prediction**:
  - Access the diabetes prediction page at `/diabetes/`.
  - Submit form data to `/predictdiabetes/` to get the prediction result.

### References

1. Diabetes Prediction Dataset https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
2. Heart Disease Prediction Dataset https://www.kaggle.com/code/nagavedareddy/heart-disease-prediction

