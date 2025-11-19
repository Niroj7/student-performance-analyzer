## 🚀 Live Streamlit Dashboard
🔗 https://students-preformance.streamlit.app/

<!-- Banner -->
<p align="center">
  <img src="banner.png" width="100%" />
</p>

# 📊 Student Performance Analyzer

An interactive **Student Performance Analyzer** built with **Python + Streamlit**.  
It processes student grade data, computes insights, and visualizes academic trends using  
clean charts and dashboards.

This tool helps identify:
- Top-performing students  
- Subject-wise strengths/weaknesses  
- Class-level statistics  
- Grade distribution  
- Performance comparisons  

---

## 🚀 Features

### ✔️ **1. Automatic Calculations**
- Per-subject averages  
- Highest and lowest scoring students  
- Class wide average  
- Automatic A–F grade assignment  
- Outlier detection support  

### ✔️ **2. Interactive Visual Charts**
- 📊 Subject-wise average score bar chart  
- 📉 Highest vs lowest scoring subjects  
- 🏅 Top 10 student performance chart  
- 🥧 Grade distribution pie chart  
- 📈 Histogram of average score distribution  
- 🧩 Combined chart showing top 3 students per subject  

### ✔️ **3. Streamlit Dashboard**
- Clean UI with easy navigation  
- Upload CSV & automatically analyze data  
- Compare two individual students  
- Compare multiple students together  
- Download cleaned / processed CSV  
- Automatically refreshes charts on data upload  

---

## 📁 Project Structure

student-performance-analyzer/
│
├── 📄 [Students_grade.csv](./Students_grade.csv)
│     └── Raw dataset containing student exam scores.
│
├── 🧮 [grade_analyzer.py](./grade_analyzer.py)
│     └── Core logic for calculations (averages, grading, analytics).
│
├── 📊 [dashboard.py](./dashboard.py)
│     └── Streamlit dashboard UI for charts, comparisons, and insights.
│
├── 📝 [README.md](./README.md)
│     └── Main documentation for the project.
│
├── 🖼️ charts/
│     ├── [subject_average_scores.png](./subject_average_scores.png)
│     ├── [subject_highest_lowest_scores.png](./subject_highest_lowest_scores.png)
│     ├── [top10_students.png](./top10_students.png)
│     ├── [grade_distribution_pie.png](./grade_distribution_pie.png)
│     ├── [average_score_distribution.png](./average_score_distribution.png)
│     ├── [top3_subjects.png](./top3_subjects.png)
│     └── Pre-generated charts used in the README & dashboard.
│
└── 📦 [requirements.txt](./requirements.txt)
      └── Python dependencies required to run the project.

---

## 🛠️ Technologies Used
- **Python**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Plotly**

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Niroj7/student-performance-analyzer.git
cd student-performance-analyzer

Install dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit dashboard
streamlit run dashboard.py

🧪 Sample Dataset

A sample dataset (Students_grade.csv) is included so you can run everything instantly.
