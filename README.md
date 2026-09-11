# 📊 Student Performance Analytics Dashboard

A Python-based **Student Performance Analytics Dashboard** built using **NumPy and Matplotlib**.

This project analyzes student academic performance through different data visualizations such as subject-wise marks, student rankings, study hours, average marks, pass/fail analysis, and performance heatmaps.

---

## 📌 Project Overview

The dashboard analyzes the performance of **8 students** across three subjects:

* 🐍 Python
* 💻 DSA
* 🗄️ DBMS

It also analyzes the relationship between **study hours and average marks** and identifies the **top-performing students**.

---

## 📊 Dashboard Preview

![Student Performance Dashboard](screenshots/dashboard.png)

---

## ✨ Features

* 📊 Subject-wise Performance Analysis
* 📈 Study Hours vs Average Marks
* 🏆 Student Ranking
* 📉 Average Marks Distribution
* 📦 Subject Marks Boxplot
* 📊 Subject Average Comparison
* 🥧 Pass/Fail Analysis
* 🥇 Top 3 Students
* 🔥 Student Performance Heatmap

---

## 📈 Visualizations

### 1. Subject Performance

A grouped bar chart comparing each student's marks in:

* Python
* DSA
* DBMS

### 2. Study Hours vs Performance

A scatter plot showing the relationship between students' study hours and their average marks.

A trend line is also used to understand the overall relationship.

### 3. Student Ranking

Students are ranked according to their average marks, from highest to lowest.

### 4. Average Marks Distribution

A histogram is used to visualize the distribution of students' average marks.

### 5. Subject Marks Boxplot

A boxplot is used to compare the distribution of marks in Python, DSA, and DBMS.

### 6. Subject Average Comparison

A bar chart compares the overall average marks of Python, DSA, and DBMS.

### 7. Pass/Fail Analysis

A pie chart shows the proportion of students who passed and failed based on the defined passing marks.

### 8. Top 3 Students

A bar chart displays the three highest-performing students based on their average marks.

### 9. Student Performance Heatmap

A heatmap provides a visual comparison of marks obtained by students across Python, DSA, and DBMS.

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Matplotlib**

---

## 📂 Project Structure

```text
student-performance-dashboard/
│
├── student_dashboard.py
├── README.md
├── requirements.txt
├── .gitignore
│
└── screenshots/
    └── dashboard.png
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd student-performance-dashboard
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Run the following command:

```bash
python student_dashboard.py
```

The dashboard will be generated using Matplotlib.

---

## 📦 Requirements

The project requires:

```text
matplotlib
numpy
```

These dependencies are also available in `requirements.txt`.

---

## 🎯 Learning Objectives

This project helped me practice:

* Python data visualization
* NumPy operations
* Matplotlib charts
* Data sorting and ranking
* Average and statistical calculations
* Working with multiple datasets
* Data analysis
* Dashboard design
* Presenting data through visualizations

---

## 🚀 Future Improvements

Some planned improvements include:

* Add CSV/Excel data input
* Add interactive charts
* Add student filtering
* Add more subjects
* Add automated performance reports
* Add student-wise detailed reports
* Convert the dashboard into a web application using Streamlit

---

## 👩‍💻 Author

**Tasneem Fatma**

MCA Student | Python | Data Visualization | Web Development

---

## ⭐ Conclusion

This project demonstrates how **Python, NumPy, and Matplotlib** can be used to transform student academic data into meaningful visual insights.

It is a practical data visualization project focused on understanding and presenting student performance effectively.
