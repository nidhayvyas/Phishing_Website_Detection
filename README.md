# Phishing Website Detection Using Machine Learning

## Project Summary
Developed an end to end machine learning pipeline to detect phishing websites by extracting and analyzing URL based features. The system classifies URLs as phishing or legitimate using supervised learning algorithms and evaluates model performance across multiple classifiers.

This project demonstrates practical experience in data preprocessing, feature engineering, model training, and evaluation using Python based machine learning frameworks.

---

## Key Skills and Technologies
- Programming: Python
- Data Analysis: Pandas, NumPy
- Machine Learning: Scikit learn, XGBoost
- Models: Decision Tree, Random Forest, Support Vector Machine (SVM)
- Data Visualization: Matplotlib, Seaborn
- Feature Engineering: URL lexical features, domain based attributes
- Tools: Git, GitHub

---

## Project Architecture

```text
.
├── project_p1.py      # Data collection and feature extraction
├── project_p2.py      # Model training, evaluation, and comparison
├── data/              # Local datasets (CSV files)
└── README.md

```

---

## Data Collection and Feature Engineering
Collected phishing and benign URLs from public datasets and engineered structured features including:

- URL length and structure
- Presence of IP address in URL
- Number of subdomains and special characters
- Domain registration and age based features
- Lexical and host based indicators

The processed dataset is stored as `urldata.csv` and used for supervised model training.

---

## Model Training and Evaluation
Implemented and evaluated multiple classification algorithms:

- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

Models were compared using accuracy metrics to identify the most effective approach for phishing detection.

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/nidhayvyas/Phishing_Website_Detection.git
cd Phishing_Website_Detection

# Install dependencies
pip install -r requirements.txt

# Run feature extraction
python project_p1.py

# Train and evaluate models
python project_p2.py
```




