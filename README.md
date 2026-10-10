# ❤️ Heart Disease Prediction Using Machine Learning

An end-to-end beginner machine learning project that uses the **K-Nearest Neighbors (KNN)** algorithm to predict the likelihood of heart disease based on user-provided health information. The project includes a Python-based machine learning model and an interactive web application built with Streamlit.

🚀 **Live Demo:** [Try the Heart Disease Prediction App](https://heart-diseaseprediction-ml.streamlit.app/)

💻 **GitHub Repository:** [Heart Disease Prediction ML](https://github.com/Bandish04/heart-disease-prediction-ML)

---

## 📌 Project Overview

The goal of this project is to explore how machine learning can be applied to healthcare-related prediction tasks. A K-Nearest Neighbors classifier is used to make predictions from input health measurements, and Streamlit provides a simple interface for interacting with the model.

This is my **first machine learning project**, built to develop practical experience with data preprocessing, model training, saving machine learning artifacts, and deploying a Python application.

## 🎯 Objectives

- Understand the fundamentals of supervised machine learning.
- Apply the K-Nearest Neighbors (KNN) classification algorithm.
- Work with a heart disease dataset for prediction.
- Use Python and Scikit-learn for machine learning.
- Build an interactive application using Streamlit.
- Save and load trained model artifacts using Joblib.
- Deploy the application using Streamlit Community Cloud.

## 🧠 Machine Learning Model

**Selected algorithm:** K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm used for classification. It predicts the class of a new data point by examining the classes of its nearest neighbors in the training dataset.

| Component | Description |
|---|---|
| Problem type | Classification |
| Selected model | K-Nearest Neighbors (KNN) |
| Machine learning library | Scikit-learn |
| Model serialization | Joblib |
| User interface | Streamlit |
| Programming language | Python |

The trained model is saved as `knn_heart.pkl` so the application can load the classifier without training it again every time the app runs.

**Preprocessing:** If feature scaling was used during training, the same fitted scaler must be applied to new input data before prediction. If the application requires `heart_scaler.pkl`, this file must also be included in the repository.

## 📊 Dataset Information

- **Dataset name:** Add the exact dataset filename.
- **Dataset source:** Add the original source URL or dataset provider.
- **Target variable:** The dataset column representing the presence or absence of heart disease.
- **Task:** Predict the target class from selected health-related features.

The dataset name, source, features, and preprocessing steps should match the actual files and training code used in this project.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Scikit-learn** — Machine learning and preprocessing
- **Joblib** — Saving and loading trained model artifacts
- **Streamlit** — Interactive web application
- **Git and GitHub** — Version control and project hosting
- **Streamlit Community Cloud** — Application deployment

## ✨ Application Features

- Interactive interface for entering health-related measurements.
- Machine learning predictions using a trained KNN classifier.
- Integration of a saved model artifact.
- Web-based access through Streamlit.
- Online deployment through Streamlit Community Cloud.

## ScreenShots
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/6a88bd5c-94dc-486b-9434-41052560753a" />
<img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/71538bd5-a891-437b-86c5-134b93d94ddd" />



## 📂 Project Structure

```text
heart-disease-prediction-ML/
│
├── app.py                   # Streamlit application
├── knn_heart.pkl            # Saved KNN model
├── heart_scaler.pkl         # Fitted scaler, if required
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
└── .gitignore               # Files excluded from Git
```

The dataset and model-training script can also be included if they are part of the project and you are permitted to redistribute the dataset.

## ⚙️ Installation and Setup

Follow these steps to run the application locally.

### 1. Clone the repository

```bash
git clone https://github.com/Bandish04/heart-disease-prediction-ML.git
```

### 2. Navigate to the project directory

```bash
cd heart-disease-prediction-ML
```

### 3. Create a virtual environment

```bash
python3 -m venv .venv
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Streamlit application

```bash
streamlit run app.py
```

The application should open in your browser. If it does not, Streamlit will display a local URL in the terminal.

**Important:** Ensure all required model files are present and that the dependencies in `requirements.txt` match the imports used in `app.py`.

## 📦 Model Artifacts

The application uses a serialized model file:

- `knn_heart.pkl` — Saved KNN classifier.
- `heart_scaler.pkl` — Fitted feature scaler, if required by the application.

These files must be generated from the training process and loaded consistently with the preprocessing used during training. Do not create an empty scaler file or fit a new scaler on individual prediction inputs.

## 🚀 Deployment

The application is deployed using Streamlit Community Cloud.

**Live application:** [https://heart-diseaseprediction-ml.streamlit.app/](https://heart-diseaseprediction-ml.streamlit.app/)

The deployed application uses the code and required files available in the connected GitHub repository. After pushing updates to GitHub, verify that the deployment rebuilds successfully.

## 📚 What I Learned

Through this project, I gained practical exposure to:

- Building a machine learning classification project.
- Working with Python data science libraries.
- Understanding the role of feature preprocessing in KNN.
- Saving and loading trained machine learning models.
- Integrating a model into a Streamlit application.
- Managing project files with Git and GitHub.
- Deploying a Python application online.

## 🔮 Future Improvements

- Add evaluation metrics such as accuracy, precision, recall, F1-score, and a confusion matrix.
- Compare KNN with other classification algorithms.
- Improve input validation and error handling.
- Document the dataset, selected features, and preprocessing pipeline in detail.
- Add tests for preprocessing and prediction.
- Improve the user interface and prediction explanations.

## ⚠️ Disclaimer

This project is for **educational and demonstration purposes only**. It is not a medical device and must not be used to diagnose heart disease, assess personal medical risk, or replace professional medical advice.

## 👨‍💻 Author

**Bandish Vaidya**

- GitHub: [@Bandish04](https://github.com/Bandish04)
- Project Repository: [Heart Disease Prediction ML](https://github.com/Bandish04/heart-disease-prediction-ML)
- Live Demo: [Heart Disease Prediction App](https://heart-diseaseprediction-ml.streamlit.app/)

---

*Built as my first machine learning project while learning Python, Scikit-learn, and model deployment.*
