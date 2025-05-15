# Rock vs Mine Prediction

**Rock vs Mine Prediction** is a machine learning project developed in Python that classifies sonar signals to determine whether an object is a rock or a mine. This project utilizes the Sonar dataset from the UCI Machine Learning Repository and implements various classification algorithms to achieve accurate predictions.

## 📊 Dataset

The dataset contains 208 instances with 60 numerical features each, representing sonar signal returns. Each instance is labeled as either 'R' (rock) or 'M' (mine). The dataset is included in the repository as `Sonar data.csv`.

## 🛠️ Prerequisites

- **Python 3.x**
- **Required Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Install the dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 📦 Installation

1. **Clone the Repository**:

```bash
git clone https://github.com/Vinayakrai/Rock-vs-Mine-Prediction.git
cd Rock-vs-Mine-Prediction
```

2. **Open the Notebook**:

Use Jupyter Notebook or any compatible IDE to open `Rock Vs Mine Prediction.ipynb`.

## 🚀 Usage

1. **Load the Dataset**:

The notebook reads the `Sonar data.csv` file and loads it into a pandas DataFrame.

2. **Data Preprocessing**:

The data is preprocessed by encoding the labels, splitting into training and testing sets, and standardizing the features.

3. **Model Training**:

A classification algorithm (e.g., Logistic Regression, SVM) is trained on the training data.

4. **Model Evaluation**:

The trained model is evaluated on the test data using metrics such as accuracy, confusion matrix, and classification report.

5. **Prediction**:

The model can predict whether a new sonar signal corresponds to a rock or a mine.

## 📁 Project Structure

```
Rock-vs-Mine-Prediction/
├── Rock Vs Mine Prediction.ipynb   # Main Jupyter Notebook
├── Sonar data.csv                  # Dataset file
└── README.md                       # Project documentation
```

