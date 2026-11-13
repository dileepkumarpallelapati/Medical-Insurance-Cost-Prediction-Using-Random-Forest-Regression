# Medical Insurance Cost Prediction Using Random Forest Regression

## About the Project

Medical Insurance Cost Prediction is a Machine Learning project that predicts the medical insurance cost based on a person's personal and health-related details.

The application uses a trained Random Forest Regression model to estimate the insurance cost in Indian Rupees (₹).

Users can enter their details through a simple Streamlit web interface and get the predicted insurance cost.

## Technologies Used

- Python
- Machine Learning
- Random Forest Regression
- NumPy
- Pandas
- Streamlit
- Pickle

## Input Features

The application takes the following inputs:

1. Age
2. Diabetes
3. Blood Pressure Problems
4. Any Transplants
5. Any Chronic Diseases
6. Height
7. Weight
8. Known Allergies
9. Family History of Cancer
10. Number of Major Surgeries

## Project Structure

Medical_Insurance_Prediction/
│
├── app.py
├── MIPML.pkl
├── requirements.txt
└── README.md

## Installation and Setup

**Step 1: Install Python**

Install Python on your computer.

**Step 2: Clone the Repository**

git clone https://github.com/dileepkumarpallelapati/Medical-Insurance-Cost-Prediction-Using-Random-Forest-Regression/edit/main/README.md

**Step 3: Open the Project Folder**

cd Medical_Insurance_Prediction

**Step 4: Install Required Libraries**

pip install -r requirements.txt

**Step 5: Run the Application**

streamlit run app.py

**Step 6: Open the Application**

Open the local URL displayed in your terminal.

**Step 7: Get Prediction**

Enter the required details and click the **Predict** button to view the estimated medical insurance cost.

## Output

The application displays the predicted medical insurance cost in Indian Rupees (₹) based on the entered details.

## Conclusion

This project demonstrates how Machine Learning can be used to estimate medical insurance costs based on personal and health-related information.

It provides a simple and user-friendly interface using Streamlit.

**Note:** The predicted insurance cost is an estimate and should not be considered an actual insurance quotation.
