# 🚢 Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

This project is the second task of my internship at **Prodigy InfoTech**. The objective was to perform **data cleaning** and **exploratory data analysis (EDA)** on a real-world dataset to identify key patterns and relationships in the data.

---

## 📁 Dataset Details

- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **File Used:** `train.csv`
- **Description:** Information about 891 passengers aboard the RMS Titanic, including features like age, gender, class, and survival status.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Handle missing data and irrelevant features.
- Visualize survival rates based on various variables.
- Identify key trends and relationships between variables.

---

## 🧰 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 🔧 Data Cleaning Steps

- Filled missing `Age` values using the median.
- Filled missing `Embarked` values using the most frequent value.
- Dropped the `Cabin` column due to over 75% missing data.
- Checked data types, null values, and basic statistics.

---

## 📊 Exploratory Data Analysis (EDA)

### 1. ✅ Survival Count

![Chart 1](screenshots/chart1.png)

---

### 2. ✅ Survival by Gender

![Chart 2](screenshots/chart2.png)

---

### 3. ✅ Survival by Passenger Class

![Chart 3](screenshots/chart3.png)

---

### 4. ✅ Age Distribution of Passengers

![Chart 4](screenshots/chart4.png)

---

### 5. ✅ Correlation Heatmap

![Chart 5](screenshots/chart5.png)

---

## 🔍 Key Insights

- **Female passengers had a much higher survival rate** than male passengers.
- **1st class passengers were more likely to survive** than those in 2nd or 3rd class.
- **Younger children had relatively higher survival rates.**
- `Embarked` and `Fare` had minor influence on survival.
- `Cabin` column was excluded due to heavy missing data.

---


---

## ▶️ How to Run

1. Make sure you have the required packages:
    ```bash
    pip install pandas matplotlib seaborn
    ```

2. Place `train.csv` in the project folder.

3. Run the script:
    ```bash
    python titanic_eda.py
    ```

---

## 🙋‍♂️ Author

**Suzal Chouhan**  
Intern at Prodigy InfoTech

---
