# 📊 Student Course Completion Prediction Dashboard  
### Final Project in Data Analytics (C301 – 7ANALYTICS)

---

## 👥 Group 7
- Bulotano, Hana Mae P.  
- Lobo, Alexander  
- Reyes, Jael  
- Tisoy, Glory Ann  

**Instructor:** Ma’am Marsha Superio  
**Date Submitted:** May 15, 2026  

---

## 📌 I. General Overview

This project is focused on analyzing student engagement, course performance, and online learning behavior using data analytics techniques and interactive dashboard visualization. The study utilized a real-world dataset containing student information, course details, engagement metrics, and completion records to identify important trends and patterns within an online learning environment.

Overall, the project demonstrated how data analytics and visualization tools helped interpret large datasets, transform raw information into meaningful insights, and support data-driven decision-making in an educational context. The findings provided a clearer understanding of how student engagement influenced course completion and performance, highlighting the importance of consistent participation and effective learning strategies in online education. Through the use of structured data modeling and interactive dashboards, the study made complex data more accessible and easier to interpret for stakeholders such as educators, administrators, and curriculum developers. This enabled them to identify areas for improvement, design targeted interventions, and enhance the overall learning experience.

---

## 📊 II. Dataset Collection

### 📁 Dataset
**Student Course Completion Prediction Dataset**

### 🔗 Source
https://www.kaggle.com/datasets/nisargpatel344/student-course-completion-prediction-dataset

### 🧾 Description
- As noted by the publisher (NISARG  PATEL), this dataset provides detailed information about students enrolled in various online courses. It includes demographic, behavioral, and performance features to predict whether a learner will complete the course or drop out.

### 📦 Dataset Size
- **Total Records:** 100,000  
- **Total Columns:** 40  
- **Format:** CSV  

---

## 🧹 III. Data Preprocessing

The dataset was cleaned using the **CLEAN Framework** to ensure accuracy, consistency, and reliability.

### a. Conceptualize the Data
- Each row represents a student enrolled in a course  
- Identified key metrics and dimensions  

**Key Metrics:**
- Total Active Students  
- Completion Rate  
- Dropout Rate  
- Average Progress  
- Average Quiz Score  
- Average Project Grade  
- Average Time Spent  
- Average Login Frequency  
- Average Session Duration  
- Satisfaction Rating  

**Key Dimensions:**
- `student_dim`  
- `course_dim`  
- `city_dim`  

---

### b. Locate Solvable Problems
- Removed duplicate records  
- Fixed inconsistent formatting  

---

### c. Evaluate Unsolvable Issues
- Applied normalization  
- Converted data types
![StarSchema](Final-Project-DA/images/Final_Project-StarSchema.png)

---

### d. Augment the Data
- Enhanced dataset for analysis and visualization  

---

### e. Note and Document
- All preprocessing steps were documented  

---

## 📈 IV. Exploratory Data Analysis (EDA)

### 📊 Summary Statistics

**Measures of Central Tendency**
- Mean Quiz Score  
- Mean Project Grade  
- Mean Progress  
- Mean Satisfaction Rating  

**Frequency & Count Measures**
- Total Active Students  
- Total Enrollments  
- Completed vs Non-completed Students  

**Distribution Analysis**
- Gender  
- Employment Status  
- Course Level  
- Device Type  
- Internet Quality  

---

### 📌 KPIs Used

**Strategic KPIs:**
- Total Active Students  
- Completion Rate  
- Dropout Rate  
- Average Progress  
- Average Satisfaction Rating  

---

### 📊 Visualizations
- Bar Charts  
- Line Graphs  
- Pie Charts  
- KPI Cards  
- Tables and Matrices  
- Slicers and Filters  

---

## 🧩 V. Data Modeling and Analytics

### ⭐ Star Schema

| Table Name     | Type            | Description |
|----------------|----------------|------------|
| fact_tbl       | Fact Table     | Stores measurable student data |
| student_dim    | Dimension Table| Student demographics |
| courses_dim    | Dimension Table| Course information |
| city_dim       | Dimension Table| Geographic data |
| cleaned_dataset| Source Table   | Cleaned dataset |

---

### 📊 Descriptive Analytics

**1. Trend Analysis**
- Monthly enrollment  
- Revenue trends  
- Completion trends  

**2. Performance Analysis**
- Quiz scores  
- Project grades  
- Course completion  

**3. Behavioral Analysis**
- Login frequency  
- Session duration  
- Device usage  
- Internet quality impact  

**4. Comparative Analysis**
- Gender  
- Employment status  
- Course level  
- Course category  

---

## 📊 VI. Dashboard

The dashboard was designed using the **DASH Framework**.

### D — Decision
Supports:
- Monitoring completion and dropout rates  
- Evaluating course effectiveness  

---

### A — Audience
- Educators  
- Developers  

Designed to be **user-friendly and accessible** for non-technical users.

---

### S — Signal (Key Indicators)
- Total Active Students  
- Completion Rate  
- Dropout Rate  
- Average Progress  
- Average Quiz Score  
- Average Project Grade  
- Login Frequency  
- Session Duration  
- Satisfaction Rating  
- Enrollment Trends  

---

### H — Hierarchy
1. KPI Cards (Top)  
2. Charts & Visualizations  
3. Filters & Slicers  

---

## 📷 Dashboard Preview

### 🔍 Overview
![Overview](Final-Project-DA/images/Final_Project-Overview.png)

### 📚 Courses Analysis
![Courses](Final-Project-DA/images/Final_Project-Courses.png)

### 📈 Engagement Analysis
![Engagement](Final-Project-DA/images/Final_Project-Engagemennt.png)

---

## 💡 VII. Insights and Recommendations

### 🔍 Key Insights

1. Students with higher engagement complete courses more successfully  
2. Advanced courses have lower completion rates  
3. Poor internet quality reduces engagement and performance  
4. Most students use mobile devices  
5. Higher-performing students show higher satisfaction  

---

### ✅ Recommendations

- Encourage active participation (reminders, gamification)  
- Provide support for advanced courses  
- Optimize platform for mobile devices  
- Support low-bandwidth users  
- Monitor student performance regularly  

---

## 🌍 Real-World Interpretation

The findings emphasize that:
- Engagement is critical to student success  
- Accessibility impacts learning outcomes  
- Platform design should support diverse users  

Improving these areas can significantly enhance **online education effectiveness**.

---

## 👥 Prepared by

**Group 7**
- Bulotano, Hana Mae P.  
- Lobo, Alexander  
- Reyes, Jael  
- Tisoy, Glory Ann  

---

## 📬 Submitted to

Ma’am Marsha Superio  
Instructor, 7Analytics  
