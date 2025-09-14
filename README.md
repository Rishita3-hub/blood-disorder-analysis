# Blood Disorder Data Analysis

This project focuses on analyzing synthetic clinical data related to blood disorders, particularly anemia. Using Python and its data science libraries, the project explores hematological parameters such as hemoglobin (HGB), red blood cell count (RBC), platelet count (PLT), and others to uncover patterns, correlations, and insights useful for early diagnosis and management.

## 🟠 Project Overview

Blood disorders like anemia are a significant health concern worldwide. This project simulates real-world patient data, processes and visualizes it using Python tools, and extracts meaningful relationships between various clinical parameters. The goal is to aid clinical decision-making and enhance the understanding of anemia's prevalence and characteristics.

## ✅ Features

- Synthetic dataset generation mimicking real patient health records.
- Data preprocessing including handling missing values, removing duplicates, and outlier detection.
- Exploratory Data Analysis (EDA) using visualizations such as scatter plots, heatmaps, and correlation matrices.
- Anemia classification by age and gender-specific thresholds.
- Analysis of anemia types: Microcytic, Normocytic, and Macrocytic.
- Automated reports using Sweetviz for data quality insights.

## 🛠 Technologies Used

- **Python** – Main programming language.
- **Pandas** – Data manipulation and cleaning.
- **NumPy** – Numerical computations.
- **Matplotlib & Seaborn** – Data visualization.
- **Sweetviz** – Automated data analysis report.
- **Google Colab** – Cloud-based coding environment.

## 📂 Dataset

- Format: `.xlsx`
- Features include Patient ID, Age, Sex, RBC, PCV, MCV, MCH, RDW, WBC, MCHC, PLT, HGB.
- 10,000 synthetic records simulating diverse demographics.

## 📖 Methodology

1. Data cleaning and preprocessing.
2. Handling missing values through mean imputation and formula-based calculations.
3. Outlier detection using the Interquartile Range (IQR).
4. Age categorization into Teen, Young Adult, Adult, Middle-aged, and Senior.
5. Visual analysis of patterns and correlations.
6. Anemia classification and exploration of subtypes.

## 📊 Visualizations

- Heatmaps of missing data.
- Correlation matrix of blood parameters.
- Scatter and line plots for paired relationships.
- Pie charts for anemia distribution and types.
- Boxplots for outlier detection.

## 📌 Key Findings

- Strong correlations between RBC and Packed Cell Volume (PCV).
- Classification of anemia based on hemoglobin and RBC counts.
- Insights into the distribution of anemia types across age groups.
- Identification of trends that can support clinical diagnostics.

## 🚀 Future Work

- Expand the dataset to include more biomarkers and demographic diversity.
- Incorporate longitudinal data for predictive modeling.
- Apply machine learning techniques to classify anemia types and severity.
- Integrate with healthcare tools for real-time diagnostic support.

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Sweetviz Documentation](https://github.com/fbdesignpro/sweetviz)
- [Health Articles on Hemoglobin and MCH](https://www.healthline.com/health/mch)

---

### 📥 Installation & Usage

```bash
# Clone this repository
git clone https://github.com/yourusername/blood-disorder-analysis.git

# Navigate to the project folder
cd blood-disorder-analysis

# Install required libraries
pip install pandas numpy matplotlib seaborn sweetviz

# Open the Jupyter notebook or Google Colab to start exploring the analysis
