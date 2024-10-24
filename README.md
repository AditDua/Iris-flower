# Iris Flower Species Prediction App

## Overview

The Iris Flower Species Prediction App is a Streamlit application that allows users to predict the species of Iris flowers based on their physical measurements. This app uses machine learning models, including Support Vector Machine (SVM), Logistic Regression, and Random Forest Classifier, to classify Iris species from the popular Iris dataset.

## Features

- User-Friendly Interface: A simple and intuitive sidebar for inputting flower measurements.
- Multiple Classifier Options: Choose between SVM, Logistic Regression, and Random Forest Classifier to see how different models perform.
- Prediction and Accuracy Display: Get predictions for the species of Iris flower along with the accuracy of the selected model.
- Interactive Sliders: Input flower measurements using sliders for a more engaging user experience.

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for potential future visualizations)
- Seaborn (for potential future visualizations)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/yourusername/iris-flower-prediction-app.git

2. Navigate to the project directory:
   cd iris-flower-prediction-app

3. Create a virtual environment (optional but recommended):
   python -m venv venv

4. Activate the virtual environment:
   - On Windows: venv\Scripts\activate
   - On macOS/Linux: source venv/bin/activate

5. Install the required packages:
   pip install -r requirements.txt

   If you don't have a requirements.txt, you can install the necessary packages individually:
   pip install streamlit pandas numpy scikit-learn matplotlib seaborn

## Usage

1. Run the application:
   streamlit run improved_iris_app.py

2. Access the app: Open your web browser and go to http://localhost:8501 to view the app.

3. Input Measurements: Use the sliders in the sidebar to set the values for Sepal Length, Sepal Width, Petal Length, and Petal Width. Select the desired classifier from the dropdown menu.

4. Make a Prediction: Click the "Predict" button to see the predicted species and the accuracy score of the selected model.

## Dataset

The application uses the Iris dataset, which includes measurements for three species of Iris flowers:
- Iris-setosa
- Iris-virginica
- Iris-versicolor

The dataset file iris-species.csv should be placed in the project directory.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any suggestions or improvements are welcome!

## License

This project is open-source and available under the MIT License.
