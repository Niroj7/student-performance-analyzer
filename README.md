# 📊 Student Performance Analyzer  
**Interactive dashboard for analyzing student grades, averages, subject-wise trends, and top performers using Python + Streamlit.**

---

## 🌐 **Live Dashboard**
👉 https://students-preformance.streamlit.app/

---

## 🖼️ Banner  
<p align="center">
  <img src="banner.png" width="100%" />
</p>

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



---

# 🧰 Technologies Used

- **Python**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Plotly**

---

# 🖥️ Dashboard Screenshots

## 📌 Class Overview  
<img src="Screenshots/AVERAGE SCORE.png" width="85%" />

---

## 📌 Subject-Wise Performance  
<img src="Screenshots/STUDENT PERFORMANMCE SUBJECT.png" width="85%" />

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

# ▶️ How to Run Locally

### **1. Clone the repo**
```bash
git clone https://github.com/Niroj7/student-performance-analyzer.git
cd student-performance-analyzer

2. Install dependencies
pip install -r requirements.txt

3. Run Streamlit app
streamlit run dashboard.py

📥 Dataset
The sample student dataset is available in:
Students_grade.csv




