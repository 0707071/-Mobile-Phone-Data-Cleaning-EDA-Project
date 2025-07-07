# 📱 Mobile Phone Data Cleaning, Imputation & EDA Project

**Author:** Muhammad Ali Mumtaz  

---

## 📝 Project Overview

This project showcases how to clean, prepare, and analyze real-world mobile phone specification data using **production-ready**, **modular**, and **reusable Python scripts**. It is structured across three Jupyter notebooks (built in Google Colab), with each notebook focusing on a key data workflow:

---

## 🧠 Project Goals

- Handle real-world messy and misaligned data  
- Build reusable and scalable cleaning functions  
- Perform logical + statistical imputation  
- Create customizable EDA visualizations  
- Prepare the dataset for modeling or further ML workflows

---

## 📘 Notebooks Breakdown

### 1. `1_data_cleaning.ipynb`
- Detects and removes **feature phones**
- Identifies and fixes **left- and right-shifted data**
- Extracts and standardizes features (e.g., RAM, camera, processor)
- Removes duplicates and noisy values

### 2. `2_data_imputation.ipynb`
- Fills missing values using:
  - Group-wise means (e.g., ratings by brand)
  - Logical assumptions (e.g., missing refresh rates = 60Hz)
  - Mode or default-based filling
- Drops unhelpful features (e.g., redundant processor name)
- Sets model name as index

### 3. `3_eda_visualizations.ipynb`
- **Univariate Analysis** (Categorical & Continuous)
- **Bivariate Analysis** (Numerical vs. Categorical)
- **Statistical Tests**:
  - ANOVA for numerical–categorical
  - Chi-square for categorical–categorical
- Uses **customizable functions** with options like `top_k`, `hue`, `figsize`, etc.

---

## 🔍 Key Issues Addressed

- Incomplete data fields
- Inconsistent formats and delimiters
- Shifted data (left or right due to missing values)
- Duplicates and low-spec phones
- Missing values in RAM, card slot, camera, ratings, etc.

---

## 🧰 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn, Scipy (for stats)  
- Google Colab

---

## 📁 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/mobile-data-cleaning-EDA-project.git

2.Open each .ipynb notebook in Google Colab or Jupyter.

Run them in order:

1_data_cleaning.ipynb

2_data_imputation.ipynb

3_eda_visualizations.ipynb


📎 Known Issues
Some old devices may contain outdated specifications.

A few rows may still need deep manual review after cleaning.

Certain assumptions were made for missing values (e.g., default refresh rate of 60Hz).

🙋‍♂️ About the Author
I'm a Data Analytics passionate about solving messy real-world problems using clean, modular code.
Let’s connect on LinkedIn :www.linkedin.com/in/muhammad-ali-mumtaz-1467a0248

⭐ Contributing
If you want to improve or build upon the functions, feel free to fork and raise a pull request!

  
