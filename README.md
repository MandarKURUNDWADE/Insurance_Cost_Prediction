# Insurance Cost Prediction 💰💡

## 📝 Description 
This project aims to predict the medical insurance cost for individuals using the "insurance.csv" dataset. We will preprocess the data, train multiple regression models, evaluate their performance, and finally implement a GUI to predict the insurance cost for a new customer.

## 📊 Dataset 
The dataset used for this project is available in a CSV file named "insurance.csv".

## 🎯 Approach 
1. Display Top 5 Rows of The Dataset.
2. Check Last 5 Rows of The Dataset.
3. Find Shape of Our Dataset (Number of Rows And Number of Columns).
4. Get Information About Our Dataset Like Total Number Rows, Total Number of Columns, Datatypes of Each Column, And Memory Requirement.
5. Check Null Values In The Dataset.
6. Convert Columns From String ['sex', 'smoker', 'region'] To Numerical Values.
7. Store Feature Matrix In X and Response(Target) In Vector y.
8. Train/Test split: Split the data into a training set and a testing set.
9. Import the models: Linear Regression, Support Vector Regressor, Random Forest Regressor, Gradient Boosting Regressor.
10. Model Training: Train the models on the training set.
11. Prediction on Test Data: Predict insurance charges for the test data using the trained models.
12. Compare Performance Visually: Plot the actual insurance charges vs. the predicted charges for the first 11 test samples.
13. Evaluating the Algorithm: Evaluate the models' performance using R squared error and mean absolute error.
14. Predict Charges For New Customer: Implement a GUI to predict the insurance cost for a new customer based on user input.
15. Save Model Using Joblib: Save the trained Gradient Boosting Regressor model using Joblib.
16. GUI: Create a simple GUI using tkinter to take user input and display the predicted insurance cost.

## 📥 Installations 
To run this project, you need to have Python installed on your machine. Additionally, install the required libraries using the following command:
```bash
pip install pandas scikit-learn matplotlib seaborn joblib tkinter
```

## ⚙️ Setup 
1. Clone this repository to your local machine or download the code as a ZIP file.
2. Place the "insurance.csv" file in the same directory as the project code.
3. Open the terminal or command prompt and navigate to the project directory.
4. Run the project code using the following command:
```bash
python insurance_cost_prediction.py
```
5. A GUI window will appear, allowing you to input customer details and predict the insurance cost.

## 🛠️ Requirements 
- Python (>=3.6)
- Pandas (>=1.0.0)
- NumPy (>=1.0.0)
- Matplotlib (>=3.0.0)
- Seaborn (>=0.10.0)
- scikit-learn (>=0.24.0)
- joblib (>=0.14.0)
- tkinter (Standard library)

## 🚀 Technology Used 
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- joblib
- tkinter (for GUI)

## ▶️ Run
1. Clone or download the project repository.
2. Place the "insurance.csv" file in the project directory.
3. Install the required libraries using the mentioned command.
4. Run the project code using the specified command in the terminal or command prompt.
5. The GUI window will appear, allowing you to enter customer details and predict the insurance cost.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
