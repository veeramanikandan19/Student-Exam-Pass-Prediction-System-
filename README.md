 #-Student Performance Analysis using Machine Learning
📌 Project Overview

This project uses Machine Learning to analyze student performance and predict whether a student is likely to Pass or Fail based on various academic and personal factors.

The project performs:

Data Loading
Data Cleaning
Missing Value Handling
Label Encoding
Model Training using Random Forest Classifier
Pass/Fail Prediction
Model Evaluation
Data Visualization using Charts

This project was developed as a beginner-friendly Machine Learning project for learning data analysis and predictive modeling.

🚀 Features
Upload and load student dataset
Clean and preprocess data
Handle missing values automatically
Encode categorical variables
Train a Random Forest Machine Learning model
Predict student performance
Calculate model accuracy
Generate classification reports
Visualize results using:
Bar Chart
Pie Chart
Feature Importance Chart
🛠️ Technologies Used
Python
Pandas
Matplotlib
Scikit-learn
Google Colab
📂 Dataset

The dataset contains information such as:

Gender
Study Hours
Attendance Rate
Past Exam Scores
Parental Education Level
Internet Access at Home
Extracurricular Activities
Final Exam Score
Pass/Fail Status
Dataset Source

You can download the dataset from Kaggle:

https://www.kaggle.com/datasets/amrmaree/student-performance-prediction\


📊 Project Workflow
Upload Dataset
Load Dataset into Pandas
Clean Missing Values
Remove Duplicates
Encode Categorical Features
Split Data into Training and Testing Sets
Train Random Forest Model
Predict Student Performance
Evaluate Accuracy
Visualize Results
📈 Visualizations

The project generates:

Pass vs Fail Bar Chart

Displays the number of students predicted to pass and fail.

Pass vs Fail Pie Chart

Shows the percentage distribution of pass and fail predictions.

Feature Importance Chart

Displays which features contribute most to the prediction.

🎯 Machine Learning Model

Random Forest Classifier

Random Forest is used because it:

Handles both numerical and categorical data
Provides high accuracy
Reduces overfitting
Offers feature importance analysis

▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/student-performance-analysis.git
Install required libraries:
pip install pandas matplotlib scikit-learn
Run the Python script:
python student_performance_analysis.py
Upload the dataset when prompted.
📋 Results


Output:

student_performance_dataset.csv(text/csv) - 41671 bytes, last modified: 6/10/2026 - 100% done
Saving student_performance_dataset.csv to student_performance_dataset.csv
Dataset Loaded Successfully!

================================
DATASET PREVIEW
================================
  Student_ID  Gender  Study_Hours_per_Week  Attendance_Rate  Past_Exam_Scores  \
0       S147    Male                    31        68.267841                86   
1       S136    Male                    16        78.222927                73   
2       S209  Female                    21        87.525096                74   
3       S458  Female                    27        92.076483                99   
4       S078  Female                    37        98.655517                63   

  Parental_Education_Level Internet_Access_at_Home Extracurricular_Activities  \
0              High School                     Yes                        Yes   
1                      PhD                      No                         No   
2                      PhD                     Yes                         No   
3                Bachelors                      No                         No   
4                  Masters                      No                        Yes   

   Final_Exam_Score Pass_Fail  
0                63      Pass  
1                50      Fail  
2                55      Fail  
3                65      Pass  
4                70      Pass  

================================
MISSING VALUES
================================
Student_ID                    0
Gender                        0
Study_Hours_per_Week          0
Attendance_Rate               0
Past_Exam_Scores              0
Parental_Education_Level      0
Internet_Access_at_Home       0
Extracurricular_Activities    0
Final_Exam_Score              0
Pass_Fail                     0


<img width="486" height="353" alt="image" src="https://github.com/user-attachments/assets/f31106cf-5f4f-4ddb-9b49-3888808a00dd" />
<img width="430" height="457" alt="image" src="https://github.com/user-attachments/assets/e5d9121a-e722-4fe2-988f-51106ffdf014" />
<img width="893" height="402" alt="image" src="https://github.com/user-attachments/assets/32e243a4-2f6f-4899-b3e0-7dded2c55553" />



The model provides:

Prediction of student performance
Accuracy Score
Classification Report
Feature Importance Analysis
Visual Graphs
Author:

Veeramanikandan.S

Student | Machine Learning Beginner | AI Enthusiast

📜 License

This project is created for educational and learning purposes.

GitHub Repository Structure
student-performance-analysis/
│
├── student_performance_analysis.py
├── README.md
├── dataset/
│   └── student_performance_dataset.csv
└── screenshots/
    ├── bar_chart.png
    ├── pie_chart.png
    └── feature_importance.png
