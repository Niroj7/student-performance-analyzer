# 📊 Student Performance Analyzer  
An interactive data dashboard built with Python, Pandas, and Streamlit to analyze student grades, visualize subject trends, and compare performance.
Showcases strong skills in data analysis, visualization, and building user-friendly dashboards that turn raw data into clear insights.

---

## 🌐 **Live Dashboard**
👉 https://students-preformance.streamlit.app/

---



# 📘 Overview  
The **Student Performance Analyzer** helps you explore and visualize classroom performance through:

- Automatic calculations (averages, grades, top/lowest performers)
- Interactive charts and dashboards
- Student comparison tools
- CSV export & data processing

Built using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Streamlit**.

---

# 🚀 Features

### ✔️ **1. Automatic Calculations**
- Per-subject averages  
- Class-wide average score  
- Highest & lowest scoring students  
- Automatic A–F grade assignment  

### ✔️ **2. Visual Charts**
- Subject-wise averages  
- Highest/lowest performance  
- Top 10 students leaderboard  
- Grade distribution pie chart  
- Histogram of average scores  
- Comparison line charts  

### ✔️ **3. Streamlit Dashboard**
- Sidebar navigation  
- Compare two students  
- Compare multiple students  
- Download cleaned CSV  
- Auto-refresh on upload  

---

# 📁 Project Structure
```

student-performance-analyzer/
│
├── Students_grade.csv # Raw dataset
├── dashboard.py # Streamlit UI
├── grade_analyzer.py # Logic for calculations
├── requirements.txt # Dependencies
│
├── Screenshots/ # Dashboard images
│ ├── AVERAGE SCORE.png
│ ├── STUDENT PERFORMANMCE SUBJECTWISE.png
│ ├── SUBJECT SCORE TRENDS.png
│ ├── TOP PERFORMER.png
│ ├── STUDENTS COMPARASION.png
│
└── README.
```


---

# 🧰 Technologies Used

- **Python**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Matplotlib**

---

# 🖥️ Dashboard Screenshots

## 📌 Class Overview  
<img src="Screenshots/AVERAGE SCORE.png" width="85%" />

---

## 📌 Subject-Wise Performance  
<img width="925" height="679" alt="STUDENT PERFORAMNCE SUBJECTWISE" src="https://github.com/user-attachments/assets/fa8a8fb0-b537-474d-86f0-97bdf4cb143c" />

---

## 📌 Subject Score Trends  
<img src="Screenshots/SUBJECT SCORE TRENDS.png" width="85%" />

---

## 📌 Top 10 Students  
<img src="Screenshots/TOP PERFORMER.png" width="85%" />

---

## 📌 Student Comparison  
<img src="Screenshots/STUDENTS COMPARASION.png" width="85%" />

---

## 🖥️ How to Run Locally
---

### 🔵 Step 1 – Clone the Repository
```bash
git clone https://github.com/Niroj7/student-performance-analyzer.git
cd student-performance-analyzer
```

<b>🟡 Step 2 – Install Dependencies</b>
```
pip install -r requirements.txt
```
<b>🟢 Step 3 – Run the Streamlit App</b>
```
streamlit run dashboard.py
```
📥<b> Dataset (Included)</b>
<i>The sample student dataset is available in the repository:</i>
```
Students_grade.csv
```






