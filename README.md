# Diabetes Prediction Using Machine Learning

## 📌 Overview
This project is a **Diabetes Prediction System** built using **Support Vector Machine (SVM)**. It analyzes patient data to predict whether an individual is diabetic or not, based on various health metrics.

## 🚀 Features
- **Uses PIMA Diabetes Dataset**
- **Data Preprocessing & Standardization**
- **Train-Test Splitting for Model Evaluation**
- **Machine Learning Model: Support Vector Machine (SVM)**
- **Accuracy Score Calculation for Performance Measurement**
- **Predictive System to Classify Patients as Diabetic or Non-Diabetic**

## 📂 Dataset
The project uses the **PIMA Diabetes Dataset**, which includes features like:
- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age
- **Outcome (0 = Non-Diabetic, 1 = Diabetic)**

## 🛠️ Installation & Setup
### Prerequisites:
Make sure you have **Python 3.x** and the following libraries installed:
```bash
pip install numpy pandas scikit-learn
```

### Running the Project:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction
   ```
3. Run the script:
   ```bash
   python project_3_diabetes_prediction.py
   ```

## 🏗️ Project Structure
```
├── diabetes.csv  # Dataset file
├── project_3_diabetes_prediction.py  # Main Python script
├── README.md  # Project documentation
```

## 🧑‍💻 Model Training & Evaluation
- **Splits the dataset into training (80%) and testing (20%) sets**
- **Applies StandardScaler for data standardization**
- **Trains an SVM classifier with a linear kernel**
- **Evaluates the model using accuracy scores on training and testing data**

## 📊 Accuracy Scores
- **Training Accuracy:** ~ (Insert Accuracy Score)
- **Testing Accuracy:** ~ (Insert Accuracy Score)

## 🔍 Prediction Example
The model takes input data and predicts whether a person is diabetic:
```python
input_data = (5,166,72,19,175,25.8,0.587,51)
prediction = classifier.predict(std_data)
```
**Output:**
```
The person is diabetic
```

## 🤝 Contributing
Feel free to fork this repository and submit a pull request if you want to contribute!

## 📜 License
This project is **open-source** and available under the **MIT License**.

---
**🔗 Connect with me:** [Your GitHub Profile](https://github.com/yourusername)

