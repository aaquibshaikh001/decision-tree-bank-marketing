# 🧠 Decision Tree Classifier on Bank Marketing Dataset

This project implements a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their **demographic and behavioral data**. The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

---

## 📊 Dataset Overview

- **Source**: UCI Machine Learning Repository
- **Instances**: 45,211
- **Features**: 16
- **Target Variable**: `y` (binary classification — 'yes' or 'no')

The data is related to direct marketing campaigns conducted via phone calls by a Portuguese banking institution.

---

## 🎯 Project Objective

To train and evaluate a **Decision Tree Classifier** that can accurately predict whether a client will subscribe to a term deposit based on:

- Age
- Job
- Marital status
- Education
- Contact communication type
- Previous outcomes of campaigns
- Duration, frequency, and timing of contact
- And more...

---

## 📂 Folder Structure

decision-tree-bank-marketing/
│
├── decision_tree_bank_marketing.py # Main script with all code
├── bank.csv # Dataset (if added locally)
├── requirements.txt # List of dependencies
├── README.md # Project overview
└── .gitignore # To exclude unnecessary files

yaml
Copy
Edit

---

## 🛠️ Technologies Used

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## ⚙️ How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/decision-tree-bank-marketing.git
   cd decision-tree-bank-marketing
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the main Python script

bash
Copy
Edit
python decision_tree_bank_marketing.py
📈 Project Output
The script provides:

Accuracy score

Confusion matrix

Classification report

Feature importance chart

Decision Tree visualization

📌 Example Use Case
This model helps identify which customers are most likely to respond positively to marketing campaigns. Financial institutions can use this insight to optimize marketing strategies and increase conversion rates.

👨‍💻 Author

Aaquib Shaikh

Open to collaboration and feedback. Connect with me on LinkedIn or explore more on my GitHub profile.

🪪 License
This project is licensed under the MIT License.
