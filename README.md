# Credit Fear Clustering: Exploring Household Financial Behavior
This notebook explores household financial behavior using data from the Survey of Consumer Finances (SCF). My goal is to segment households into distinct groups based on credit fearfulness, analyzing characteristics such as assets, income, race, age, and debt.

The project follows these key steps:
✅ Exploratory Data Analysis (EDA) – Understanding trends and distributions
✅ Unsupervised Learning (Clustering) – Grouping households into meaningful clusters
✅ Interactive Dash & Streamlit Apps – Building visual tools for interpretation

# Credit Fear Clustering: Segmenting Households Based on Financial Behavior

## 📖 Overview
This project explores household financial data from the **Survey of Consumer Finances (SCF)** to segment households based on **credit fearfulness** (fear of rejection when applying for credit). We apply **unsupervised machine learning (clustering)** to identify distinct household groups using key financial attributes such as:
- 📊 **Assets & Debt**
- 🏠 **Housing & Property Ownership**
- 💰 **Income Distribution**
- 🔢 **Demographics (Age, Race, Education)**

## 🚀 Project Workflow
1. **Data Preprocessing** - Cleaning and structuring SCF data  
2. **Exploratory Data Analysis (EDA)** - Understanding patterns in the dataset  
3. **Feature Engineering** - Selecting relevant variables for clustering  
4. **Clustering (Unsupervised Learning)** - Using **K-Means & Hierarchical Clustering**  
5. **Model Evaluation** - Assessing cluster quality & interpretability  
6. **Interactive Visualization** - Dash & Streamlit app for dynamic exploration  

## 📂 Folder Structure


## 📊 Data Source
- **Survey of Consumer Finances (SCF) 2019**
- Conducted by the Federal Reserve, this dataset provides financial characteristics of U.S. households.

## 🛠️ Installation & Setup
### 1️⃣ Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/credit-fear-clustering.git
cd credit-fear-clustering


### 2️⃣ Set up a virtual environment
python -m venv venv
source venv/Scripts/activate  # Windows
# source venv/bin/activate    # macOS/Linux

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 4️⃣ Running the Jupyter Notebook
jupyter lab

### 5️⃣ Running the Dashboard (Streamlit)
cd dashboards
streamlit run app.py

