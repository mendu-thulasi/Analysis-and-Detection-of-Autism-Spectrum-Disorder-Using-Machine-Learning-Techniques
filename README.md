# Analysis-and-Detection-of-Autism-Spectrum-Disorder-Using-Machine-Learning-Techniques

A machine learning-based system for **Autism Spectrum Disorder (ASD) screening and prediction** using questionnaire-based data. The project applies multiple machine learning and deep learning algorithms, evaluates their performance, and provides a graphical interface for making predictions.

> **Note:** This project is intended for educational and research purposes. It provides preliminary screening predictions and is **not a substitute for professional medical diagnosis**.

---

## 📌 Project Overview

Autism Spectrum Disorder is a neurodevelopmental condition that can affect communication, social interaction, and behavior. Early screening can help identify individuals who may benefit from further professional evaluation.

This project develops an automated screening system that analyzes relevant questionnaire and demographic attributes using machine learning techniques. The system performs data preprocessing, model training, evaluation, comparison, and prediction through a user-friendly GUI.

---

## 🎯 Objectives

* Analyze questionnaire-based ASD screening data.
* Preprocess and prepare the dataset for machine learning.
* Implement multiple classification algorithms.
* Compare model performance using different evaluation metrics.
* Provide an interactive graphical user interface.
* Generate predictions for new/test records.
* Demonstrate the application of machine learning in healthcare screening.

---

## 🛠️ Technologies Used

| Technology             | Purpose                             |
| ---------------------- | ----------------------------------- |
| **Python**             | Core programming language           |
| **Pandas**             | Data manipulation and preprocessing |
| **NumPy**              | Numerical operations                |
| **Scikit-learn**       | Machine learning algorithms         |
| **TensorFlow / Keras** | Deep learning models                |
| **Matplotlib**         | Data visualization                  |
| **Seaborn**            | Statistical visualization           |
| **Tkinter**            | Graphical User Interface            |

---

## 🤖 Machine Learning Algorithms

The project explores several classification techniques:

* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Logistic Regression
* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN)

The models are trained using the processed dataset and evaluated to understand their classification performance.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Algorithm Comparison
   ↓
Prediction
   ↓
GUI Output
```

---

## 📊 Model Evaluation

The models are evaluated using commonly used classification metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Sensitivity**
* **Specificity**
* **Confusion Matrix**

These metrics help analyze how effectively each model identifies the two screening classes.

---

## 🖥️ Graphical User Interface

The project includes a **Tkinter-based GUI** that allows users to interact with the machine learning system.

### Main functionalities

* Load the dataset
* Preprocess the data
* Train machine learning models
* Evaluate model performance
* Visualize results
* Perform predictions on test data
* Display the prediction result

---

## 📂 Project Structure

```text
AutismScreening/
│
├── dataset/
│   └── autism_dataset.csv
│
├── models/
│   ├── model files
│   └── preprocessing files
│
├── notebooks/
│   └── analysis notebooks
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   ├── prediction.py
│   └── gui.py
│
├── requirements.txt
├── README.md
└── ...
```

*Update the folder names above if your repository uses a different structure.*

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AutismScreening.git
```

### 2. Navigate to the project directory

```bash
cd AutismScreening
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install the main dependencies:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib seaborn
```

> Tkinter is usually included with standard Python installations. On some Linux distributions, it may need to be installed separately.

---

## ▶️ Running the Project

Run the main Python file:

```bash
python app.py
```

or, depending on the project structure:

```bash
python main.py
```

The graphical interface will open and allow you to load data, train/evaluate models, and perform predictions.

---

## 📈 Results

The performance of different algorithms can be compared using accuracy, precision, recall, F1-score, sensitivity, specificity, and confusion matrices.

The comparison helps identify how different machine learning approaches behave on the selected ASD screening dataset.

---

## 🔮 Future Enhancements

* Develop a web-based interface.
* Deploy the trained model using Flask or FastAPI.
* Improve model performance through hyperparameter tuning.
* Add explainable AI techniques to improve prediction interpretability.
* Support real-time screening through an online questionnaire.
* Add secure database integration.
* Deploy the application on a cloud platform.

---

## ⚠️ Disclaimer

This project is developed for **educational and research purposes**. The predictions generated by the system should not be considered a medical diagnosis. Individuals should consult qualified healthcare professionals for clinical assessment and diagnosis.

---

## 👩‍💻 Author

**Thulasi Mendu**

B.Tech – Computer Science and Engineering (Data Science)

---

## ⭐ Acknowledgement

This project demonstrates the application of **machine learning and deep learning techniques to healthcare screening**, with a focus on exploring automated ASD screening using questionnaire-based data.

