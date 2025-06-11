# 🚲 AI-Based Bike Sales Analysis

This repository presents a complete pipeline for analyzing bike sales data and generating predictive insights using Python. The project uses a real-world dataset to explore customer trends, generate visualizations, and apply basic AI techniques to forecast bike purchase behavior.

## 📊 Dataset

- **Source**: [Kaggle – Bike Sales Sample Data](https://www.kaggle.com/datasets/yasinnaal/bikes-sales-sample-data)
- **Content**: Includes demographic and behavioral data such as:
  - Customer age, gender, income
  - Education level
  - Commute distance
  - Purchase decision (Yes/No)

## 📄 Description

This project is designed to answer key business questions such as:
- Who is most likely to purchase a bike?
- How does income or commute distance affect bike buying behavior?
- Can we predict purchase decisions based on demographics?

### Key Components

- 🔧 **Data Cleaning**: Handles missing values and formats columns
- 📊 **Exploratory Data Analysis**: Sales trends by region, gender, income, etc.
- 🧠 **AI-Based Prediction**: Uses machine learning to predict purchase decisions
- 🧪 **Testing Module**: Includes automated test script and test cases

---

## 📁 Project Structure

bike-sales-analysis/
├── data/ # Place dataset here (e.g., bike_sales.csv)
├── notebooks/
│ └── Bike_Sales_Analysis.ipynb # Main Jupyter notebook
├── tests/
│ └── test_script.py # Functional tests using pytest
├── README.md
├── .gitignore
└── LICENSE


---

## ⚙️ Setup & Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/bike-sales-analysis.git
cd bike-sales-analysis
Install dependencies:

pip install pandas matplotlib seaborn scikit-learn pytest
Download the dataset from Kaggle and place it in the /data/ folder.

▶️ Usage
Open and run the Jupyter notebook:

jupyter notebook notebooks/Bike_Sales_Analysis.ipynb
Explore:

Distribution of purchases by gender, income, and commute distance

Visualizations of trends and feature relationships

A machine learning classifier (e.g., Logistic Regression or Decision Tree) to predict bike purchase decisions

✅ Test Cases
Functional tests are provided in tests/test_script.py:

pytest tests/test_script.py
Sample test cases include:

✅ Data loading integrity

✅ Null value checks

✅ Model accuracy ≥ 80%

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Kaggle for the dataset

Open-source libraries that power this project: pandas, matplotlib, scikit-learn, seaborn, pytest

💡 Future Work
Deploy a prediction web app using Streamlit or Flask

Add more advanced classification models (e.g., XGBoost, Random Forest)

Automate data versioning with DVC or Git LFS

