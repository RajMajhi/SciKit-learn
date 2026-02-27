# SciKit-learn 
## using specific version i.e 1.8.0

## Project Overview

This project uses the **Breast Cancer Wisconsin Dataset** available in **Scikit-Learn** to build a classification model that predicts whether a tumor is malignant or benign.

The main objective is to:

* Load and understand the dataset
* Preprocess the data
* Train a machine learning model
* Evaluate its performance
* Make predictions

---

## Technologies Used

* Python 
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## Dataset

We used the built-in dataset:

* **Breast Cancer Dataset** from Scikit-Learn

It contains:

* 569 samples
* 30 numerical features
* Binary target variable (Malignant / Benign)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

Install required libraries:

```bash
pip install -r requirements.txt
```

If you don’t have a requirements file:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## How to Run

Run the main Python file:

```bash
python main.py
```

---

## Model Used

* K-Nearest Neighbors (KNN)
* (You can also mention Logistic Regression / Decision Tree if used)

Example import:

```python
from sklearn.neighbors import KNeighborsClassifier
```

---

## Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## Workflow

1. Import dataset
2. Split into training & testing sets
3. Feature scaling using StandardScaler
4. Train the model
5. Evaluate performance
6. Make predictions

---

## Sample Output

Example accuracy:

```
Model Accuracy: 96%
```

---

## Learning Outcomes

* Understanding supervised learning
* Working with real-world datasets
* Model evaluation techniques
* Improving model performance

---

## Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

## License

This project is open-source and available under the MIT License.
