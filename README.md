# Student Internship  Predictor

This is an end-to-end Machine Learning project that predicts whether a student will be placed based on two key features: **CGPA** and **IQ**.

## 🚀 Project Overview
The goal of this project is to build a classification model to assist in predicting student placement outcomes. The workflow includes:
1.  **Data Loading:** Importing the student dataset.
2.  **EDA & Preprocessing:** Analyzing data distributions and cleaning the data (e.g., removing unnecessary columns).
3.  **Model Building:** Training a Machine Learning classifier.
4.  **Evaluation:** Assessing the model's accuracy and performance.

## 📊 Dataset
The project uses a dataset (`placement.csv`) containing 100 student records with the following attributes:
* `cgpa`: Cumulative Grade Point Average of the student.
* `iq`: Intelligence Quotient score.
* `placement`: Target variable (1 if placed, 0 otherwise).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn (or TensorFlow/Keras depending on your model choice), Matplotlib/Seaborn.

## 📁 Repository Structure
* `End_to_End_ML_Project.ipynb`: The main Jupyter Notebook containing the code.
* `placement.csv`: The dataset used for training and testing.

## 📈 Results
The model analyzes the relationship between academic performance (CGPA) and IQ to predict placement success. Initial exploration shows that both features play a significant role in determining the target outcome.

## 📝 How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Student-Placement-Predictor.git](https://github.com/YOUR_USERNAME/Student-Placement-Predictor.git)
