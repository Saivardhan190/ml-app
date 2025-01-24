# Iris Flower Prediction App 🌸

This is a **Streamlit-based web application** that predicts the species of an Iris flower based on its measurements using a trained **Random Forest Classifier**. The application is built with Python and utilizes the **Iris dataset** from `sklearn.datasets`.

## Features
- Allows users to input flower measurements (sepal length, sepal width, petal length, and petal width) using an intuitive sidebar slider interface.
- Predicts the species of the Iris flower (Setosa, Versicolor, or Virginica).
- Displays the prediction and the associated probabilities for each species.
- Fully interactive and easy-to-use interface built with Streamlit.

---

## How It Works
1. The application uses a **Random Forest Classifier** trained on the Iris dataset.
2. Users input the flower's features through sliders.
3. The app displays:
   - The user input features.
   - The predicted Iris species.
   - Probabilities for each species.

---

## Installation and Usage

### Prerequisites
- Python 3.7+
- Required Python libraries: `streamlit`, `scikit-learn`, `pandas`

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone 
2.Install the required libraries:

pip install -r requirements.txt
3.Run the Streamlit app:

streamlit run app.py

## Example

### Input:
Sepal Length: 5.1 cm

Sepal Width: 3.5 cm

Petal Length: 1.4 cm

Petal Width: 0.2 cm

### Output:
Prediction: Setosa

Prediction Probabilities:

Setosa: 100%

Versicolor: 0%

Virginica: 0%

## File Structure
app.py: Main Streamlit app file containing the code for the Iris Flower Prediction App.

requirements.txt: List of Python libraries required to run the app.
## Technologies Used
Python: Core programming language.

Streamlit: For building the interactive web application.

Scikit-learn: For training and using the Random Forest model.

Pandas: For data handling and display.

## Future Enhancements
Add more advanced machine learning models for comparison.

Include data visualizations for better insights.

Add options for users to upload a CSV file of multiple Iris measurements for batch predictions.

## Credits
Dataset: Iris dataset from UCI Machine Learning Repository.

Built With: Python, Streamlit, Scikit-learn, Pandas.
## License
This project is licensed under the MIT License. See the LICENSE file for details.

