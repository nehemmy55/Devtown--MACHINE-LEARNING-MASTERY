#  Devtown Machine Learning Mastery

A comprehensive machine learning project demonstrating end-to-end data analysis and model comparison using customer retail data.

##  Project Overview

This repository contains machine learning projects and bootcamp exercises focused on building, training, and evaluating classification and regression models. The primary dataset contains customer retail transaction data with features like quantity, unit price, and geographic location.

---

##  Notebooks

### 1. **ML_Retail_Project.ipynb** - Final ML Project
The main capstone project that builds and compares multiple machine learning classifiers.

**What you'll learn:**
- Data loading and preprocessing using Pandas
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering and encoding
- Model building with multiple algorithms
- Model evaluation and comparison

**Key Models:**
-  **Logistic Regression** - Baseline classifier
-  **Decision Tree** - Tree-based classification
-  **K-Nearest Neighbors (KNN)** - Distance-based classifier

**Features Analyzed:**
- Quantity (number of items purchased)
- Unit Price (price per item)
- Country (geographic location)
- Customer segmentation and behavior

**Evaluation Metrics:**
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

**Output Visualizations:**
- Feature distributions and relationships
- Model performance comparisons
- Confusion matrices for each model
- Classification metrics

---

### 2. **day1_ML_bootcamp.ipynb** - Day 1 Bootcamp Basics
Introductory notebook covering fundamental ML concepts.

**Topics Covered:**
- **Linear Regression**: Simple real-world example (ice cream sales vs temperature)
- **Logistic Classification**: Binary classification with house prices vs size

**Skills Developed:**
- Model fitting and training
- Prediction on new data
- Understanding supervised learning fundamentals

---

##  Dataset

**File:** `customer_retail_csv_file.csv`

**Columns:**
- `InvoiceNo` - Unique transaction identifier
- `StockCode` - Product code
- `Description` - Product description
- `Quantity` - Number of items purchased
- `InvoiceDate` - Transaction date and time
- `UnitPrice` - Price per unit
- `CustomerID` - Unique customer identifier
- `Country` - Customer location

**Sample Data:**
```
536365, 85123A, WHITE HANGING HEART T-LIGHT HOLDER, 6, 01-12-2010 08:26, 2.55, 17850, United Kingdom
536365, 71053, WHITE METAL LANTERN, 6, 01-12-2010 08:26, 3.39, 17850, United Kingdom
```

---

##  Requirements

**Libraries Used:**
```
pandas          # Data manipulation
numpy           # Numerical computing
matplotlib      # Data visualization
seaborn         # Statistical visualization
scikit-learn    # Machine learning models
```

**Installation:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

##  Getting Started

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/nehemmy55/Devtown--MACHINE-LEARNING-MASTERY.git
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open notebooks in Jupyter or Google Colab**
   - Click "Open in Colab" button in notebook header, or
   - Run locally: `jupyter notebook`

4. **Run cells sequentially** to execute the analysis and model training

---

##  Project Workflow

### ML_Retail_Project Flow:
1.  Import libraries
2.  Load dataset
3.  Exploratory Data Analysis (EDA)
4.  Data preprocessing & feature encoding
5.  Train-test split
6.  Train multiple classifiers
7.  Evaluate and compare models
8.  Visualize results

---

##  Key Learning Outcomes

After completing these notebooks, you'll understand:

 **Data Science Fundamentals**
- Loading and exploring datasets
- Data cleaning and preprocessing
- Feature engineering techniques

 **Machine Learning Concepts**
- Supervised learning (classification)
- Model training and evaluation
- Model comparison and selection

 **Practical Skills**
- Using scikit-learn for ML workflows
- Data visualization with matplotlib/seaborn
- Performance metrics interpretation

---

##  Model Comparison Results

The ML_Retail_Project compares three classification algorithms:

| Model | Accuracy | Strengths | Weaknesses |
|-------|----------|-----------|-----------|
| Logistic Regression | Fast, interpretable | Assumes linear relationships |
| Decision Tree | Interpretable, handles non-linearity | Prone to overfitting |
| KNN | Simple, flexible | Computationally expensive at scale |

*Note: Specific accuracy values will be generated when notebooks are executed.*

---

##  Tips for Running the Project

1. **Start with day1_ML_bootcamp.ipynb** if you're new to ML
2. **Then move to ML_Retail_Project.ipynb** for advanced concepts
3. **Modify parameters** (e.g., number of neighbors in KNN, tree depth) to experiment
4. **Add new features** to improve model performance
5. **Try different train-test splits** to see impact on model stability

---

##  Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [ML Basics](https://developers.google.com/machine-learning/crash-course)

---

##  License

This project is part of the Devtown Machine Learning Mastery curriculum.

---

##  Author :NEHEMIE ISHIMWE

Created as part of machine learning bootcamp and mastery program.

*Last Updated: May 2026*
