# 🌸 Iris Flower Classification Project

## 📌 Project Overview
This project focuses on building a machine learning model to classify iris flowers into three different species based on their physical features. The Iris dataset is one of the most popular datasets in machine learning and is widely used for beginners to understand classification problems.

The goal of this project is to perform end-to-end data analysis including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

## 📊 Dataset Information
The dataset contains measurements of iris flowers from three different species:

- Setosa
- Versicolor
- Virginica

### Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target:
- Species (Flower type)

Each row represents a flower with its corresponding measurements.

---

## 🧹 Data Preprocessing
The dataset was cleaned and prepared for analysis using the following steps:

- Checked for missing values and handled them
- Removed duplicate records
- Converted categorical target variable into numerical form using Label Encoding
- Applied feature scaling using StandardScaler to normalize the data

---

## 📈 Exploratory Data Analysis (EDA)
EDA was performed to understand patterns and relationships in the dataset:

- Histograms were used to analyze feature distributions
- Pairplots were used to visualize relationships between features
- Scatter plots helped identify separation between different species
- Correlation heatmap was used to understand relationships between variables

### Key Observations:
- Petal length and petal width are highly correlated
- Setosa species is clearly separable from other species
- Some overlap exists between Versicolor and Virginica

---

## 🤖 Model Building
A classification model was built using Logistic Regression.

### Steps:
- Dataset split into training (80%) and testing (20%)
- Model trained on training data
- Predictions made on test data

---

## 📊 Model Evaluation
The model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### Results:
- Achieved high accuracy (~95%+)
- Model performs very well for Setosa classification
- Slight confusion between Versicolor and Virginica

---

## 🔁 Model Comparison
Additional models were also tested:

- Random Forest Classifier
- Support Vector Machine (SVM)

### Conclusion:
- Logistic Regression performed well with simplicity
- Random Forest provided comparable or better accuracy
- SVM also showed strong performance

---

## 🧠 Key Learnings
- Importance of data preprocessing
- Understanding feature relationships through EDA
- Model evaluation techniques
- Comparison between different classification algorithms

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## 🚀 Conclusion
This project successfully demonstrates the complete machine learning pipeline from data preprocessing to model evaluation. It highlights how simple models like Logistic Regression can achieve high accuracy on well-structured datasets.


## 📌 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Deploying the model using Flask or Streamlit
- Building a UI for predictions


## 👨‍💻 Author
Vansh Agarwal  
B.Tech CSE | Data Analyst Aspirant  
