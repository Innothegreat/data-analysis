# 📊 Student Exam Scores Analysis

## 📌 Overview
This project demonstrates how to **analyze a dataset of student exam scores** using **pandas** for data analysis and **matplotlib/seaborn** for data visualization.  

The dataset used is **`student_exam_scores.csv`**, which contains student performance data such as study hours, sleep hours, attendance percentage, previous scores, and exam scores.

---

## 🎯 Objectives
- Load and explore a dataset using **pandas**.  
- Perform **basic data analysis** (descriptive statistics, grouping, etc.).  
- Create **visualizations** using **matplotlib** and **seaborn**.  
- Identify **patterns and insights** about student exam performance.  

---

## 📂 Dataset
**File:** `student_exam_scores.csv`  

**Columns:**
- `student_id` → Unique student identifier  
- `hours_studied` → Number of hours studied before exam  
- `sleep_hours` → Average hours of sleep per night  
- `attendance_percent` → Attendance percentage in class  
- `previous_scores` → Previous exam/test scores  
- `exam_score` → Final exam score  

---

## 📝 Tasks Performed
### 1. Load & Explore Dataset
- Used `pandas.read_csv()` to load the dataset.  
- Inspected structure using `.head()`, `.info()`, `.isnull()`.  
- Cleaned missing values (if any).  

### 2. Basic Data Analysis
- Generated summary statistics with `.describe()`.  
- Grouped students by attendance levels (Low, Medium, High).  
- Calculated mean exam scores for each group.  

### 3. Data Visualization
Created the following visualizations:
1. **Line Chart** → Exam score trends.  
2. **Bar Chart** → Average exam scores by attendance group.  
3. **Histogram** → Distribution of hours studied.  
4. **Scatter Plot** → Relationship between hours studied and exam score.  

---

## 📊 Example Insights
- Students with **higher attendance** generally score better in exams.  
- **Hours studied** positively correlate with exam scores.  
- Some students with **low sleep hours** tend to have lower performance.  

---

## ⚙️ Requirements
Install the required Python libraries before running the notebook:

```bash
pip install pandas matplotlib seaborn
```

---

## 🚀 How to Run
1. Clone this repository or copy the notebook and dataset.  
2. Ensure the file **`student_exam_scores.csv`** is in the same directory as the notebook.  
3. Open Jupyter Notebook or Google Colab.  
4. Run the notebook **cell by cell** to see analysis and visualizations.  

---

## ✅ Conclusion
This analysis demonstrates how **pandas** and **matplotlib/seaborn** can be used to explore, analyze, and visualize student performance data. The findings provide useful insights into how **study habits, attendance, and sleep** affect exam results.  
