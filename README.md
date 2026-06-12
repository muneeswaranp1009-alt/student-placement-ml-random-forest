#  Student Placement Prediction using Random Forest

This project uses the Random Forest Machine Learning algorithm to predict whether a student is likely to get placed based on academic performance and skill-related attributes.

##  Features

- Predicts student placement status
- Uses Random Forest Classifier
- Data preprocessing and encoding
- Model training and testing
- Performance evaluation
- Confusion Matrix and Classification Report
- Data visualization using Matplotlib
- Saves the trained model using Joblib

---

##  Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

---

##  Project Structure

```
student-placement-prediction-random-forest/
│
├── students_data.csv
├── placement_model.pkl
├── placement_prediction.py
└── README.md
```

---

##  Dataset Features

The model uses the following input features:

- CGPA
- Aptitude Score
- Communication Skills
- Number of Projects
- Internship Status

### Target

- Placement (Yes / No)

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-placement-prediction-random-forest.git
```

Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn joblib
```

Run the project:

```bash
python placement_prediction.py
```

---

##  Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The project also includes graphical visualization of the dataset for better analysis.

---

##  Sample Input

```
CGPA: 8.7
Aptitude: 85
Communication: 90
Projects: 4
Internship: Yes
```

### Sample Output

```
Prediction: Placed

Probability of Placement: 94.3%
Probability of Not Placement: 5.7%
```

---

##  Learning Outcomes

- Data Preprocessing
- Feature Engineering
- Random Forest Classification
- Model Evaluation
- Data Visualization
- Model Serialization with Joblib

---

##  Future Improvements

- Build a Streamlit web application
- Compare Random Forest with other ML models
- Hyperparameter tuning for improved accuracy
- Deploy using Flask or FastAPI
- Add real-time prediction interface

---

##  Author

Developed as a Machine Learning project to predict student placement using the Random Forest algorithm.

If you found this project useful, don't forget to ⭐ star the repository!
