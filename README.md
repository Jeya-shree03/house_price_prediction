House Price Prediction using Linear Regression
This project implements a Linear Regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms using the Kaggle House Prices dataset.
📌 Project Objective
To build a machine learning model that predicts house prices by analyzing important features such as:
Living Area (Square Footage)
Number of Bedrooms
Number of Bathrooms
📊 Dataset
Source: Kaggle
Competition: House Prices – Advanced Regression Techniques
Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
File used:
train.csv
🛠️ Technologies Used
Python 🐍
Google Colab / Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
🧠 Machine Learning Model
Algorithm: Linear Regression
Library: sklearn.linear_model.LinearRegression
⚙️ Project Workflow
Downloaded dataset from Kaggle
Loaded data using Pandas
Selected relevant features
Removed missing values
Split data into training and testing sets
Trained Linear Regression model
Evaluated model using MSE and R² score
Predicted house prices for new inputs
Visualized actual vs predicted prices
📁 Project Structure
Copy code

House-Price-Prediction/
│
├── train.csv
├── House_Price_Prediction.ipynb
├── README.md
▶️ How to Run the Project
Clone this repository:
Copy code
Bash
git clone https://github.com/your-username/House-Price-Prediction.git
Open the notebook:
Copy code
Bash
House_Price_Prediction.ipynb
Upload train.csv file to the same directory
Run all cells
📈 Model Evaluation
Mean Squared Error (MSE)
R² Score
Higher R² score indicates better prediction accuracy.
🔮 Sample Prediction
The model can predict house prices for new inputs such as:
Living Area = 2000 sq.ft
Bedrooms = 3
Bathrooms = 2
🧑‍💻 Author
Jeya Shree
Engineering Student
Machine Learning Enthusiast
⭐ Acknowledgement
Thanks to Kaggle for providing the House Prices dataset.
📌 Note
This project is created for learning and academic purposes.
