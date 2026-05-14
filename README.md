# STUDENT COURSE COMPLETION PREDICTION DATASET

## Final Project Documentation in Data Analytics

### C301 – 7ANALYTICS

---

## Group Members (Group 7)

* Bulotano, Hana Mae P.
* Lobo, Alexander
* Reyes, Jael
* Tisoy, Glory Ann

## Instructor

Ms. Marsha Superio

## Date Submitted

May 15, 2026

---

# I. General Overview

This project focused on analyzing student engagement, course performance, and online learning behavior using data analytics techniques and interactive dashboard visualization. The study utilized a real-world dataset containing student information, course details, engagement metrics, and completion records to identify important trends and patterns within an online learning environment.

Overall, the project demonstrated how data analytics and visualization tools helped interpret large datasets, transform raw information into meaningful insights, and support data-driven decision-making in an educational context. The findings provided a clearer understanding of how student engagement influenced course completion and performance, highlighting the importance of consistent participation and effective learning strategies in online education.

Through the use of structured data modeling and interactive dashboards, the study made complex data more accessible and easier to interpret for stakeholders such as educators, administrators, and curriculum developers. This enabled them to identify areas for improvement, design targeted interventions, and enhance the overall learning experience.

---

# II. Dataset Collection

## Dataset Title

**Student Course Completion Prediction Dataset**

## i. Dataset Source

* [https://www.kaggle.com/datasets/nisargpatel344/student-course-completion-prediction-dataset](https://www.kaggle.com/datasets/nisargpatel344/student-course-completion-prediction-dataset)

## ii. Dataset Description

* This dataset provides detailed information about students enrolled in various online courses. It includes demographic, behavioral, and performance features to predict whether a learner will complete the course or drop out.

## iii. Dataset Size

* Total Records: 100,000
* Total Columns: 40
* File Format: CSV

---

# III. Data Preprocessing

## i. Data Cleaning Procedures Performed

The project followed the **CLEAN Framework** to ensure the dataset was accurate, consistent, reliable, and ready for analytics and visualization. The CLEAN Framework guided the preprocessing stage by organizing the cleaning procedures into systematic steps.

### a. Conceptualize the Data

The dataset was initially reviewed and analyzed to understand its structure, content, and quality before preprocessing.

Missing values were identified and addressed using appropriate techniques such as:

* Asking the right questions
* Replacing missing values using suitable methods
* Validation of corrected entries

#### What does each row represent?

Each row in the dataset represents one student enrolled in an online course along with their demographic information, learning behavior, engagement activity, academic performance, and course completion status.

#### What are the key metrics?

### Key Metrics Used in the Dashboard

* Total Active Students
* Completion Rate
* Dropout Rate
* Total Courses
* Average Progress
* Average Quiz Score
* Average Project Grade
* Average Time Spent
* Average Login Frequency
* Average Session Duration
* Average Satisfaction Rating
* Video Completion Rate
* Enrollment Trend by Month
* Number of Students per Course
* Course Completion Count

#### What are the key dimensions?

### Key Dimensions Used in the Dashboard (Dimension Tables)

* student_dim
* course_dim
* city_dim

### b. Locate Solvable Problems

Duplicate entries were detected and removed to avoid inconsistencies and inaccurate analysis.

Additional solvable problems included:

* Inconsistent formatting
* Incorrect categorical labels
* Minor data entry errors
* Redundant records

This process improved the consistency and reliability of the dataset.

### c. Evaluate Unsolvable Issues

Certain data limitations and unavoidable inconsistencies were evaluated to minimize their impact on analysis.

The dataset underwent several transformations including:

* Data normalization
* Renaming columns for readability
* Converting data types where necessary

### d. Augment the Data

The cleaned dataset was enhanced and validated to ensure accuracy, consistency, and proper structure for analytics and reporting.

This final stage prepared the dataset for:

* Exploratory data analysis
* KPI generation
* Dashboard creation
* Data-driven insights

### e. Note and Document

Every process is documented.

---

# IV. Exploratory Data Analysis (EDA)

## i. Summary Statistics Generated

The following statistical measures were generated from the `fact_tbl` to analyze student performance, engagement, enrollment behavior, and course completion trends within the dashboard.

### Measures of Central Tendency

* Mean Quiz Score
* Mean Project Grade
* Mean Progress Percentage
* Mean Satisfaction Rating
* Mean Session Duration
* Mean Login Frequency
* Mean Time Spent

### Frequency and Count Measures

* Total Active Students
* Total Revenue
* Total Course
* Total Completed Students
* Total Non-Completed Students
* Students per Course

### Percentage and Rate Measures

* Completion Rate
* Dropout Rate
* Video Completion Percentage

### Distribution Measures

* Distribution of Students by Gender
* Distribution of Students by Employment Status
* Distribution of Students by Course Level
* Distribution of Students by Device Type
* Distribution of Students by Internet Quality
* Monthly Enrollment Distribution

## ii. KPI and Measures Used

The dashboard utilized several KPIs and analytical measures following the Pyramid Framework to monitor educational performance and platform engagement.

### Strategic KPIs

* Total Active Students
* Completion Rate
* Dropout Rate
* Total Revenue
* Average Progress
* Average Satisfaction Rating

These KPIs provided high-level insights into platform performance and student success.

## iii. Visualizations Used

The dashboard included multiple visualizations such as:

* Bar Charts
* Line Graphs
* Pie Charts
* KPI Cards
* Tables and Matrices
* Slicers and Filters

These visualizations helped simplify the data and improve interpretation.

---

# V. Data Modeling and Analytics

The project applied data modeling techniques to organize and analyze the dataset efficiently.

![Image](../Final-Project-DA/images/Final_Project-StarSchema.png)

## i. Star Schema

| Table Name      | Table Type      | Description                                                                       |
| --------------- | --------------- | --------------------------------------------------------------------------------- |
| fact_tbl        | Fact Table      | Stores measurable data related to student performance, engagement, and completion |
| student_dim     | Dimension Table | Contains demographic and behavioral student information                           |
| courses_dim     | Dimension Table | Stores course-related information                                                 |
| city_dim        | Dimension Table | Contains location and geographic information                                      |
| cleaned_dataset | Source Table    | Cleaned source dataset used before modeling                                       |

## ii. Descriptive Analytics

The project applied **Descriptive Analytics** to summarize historical data and identify patterns, trends, and relationships within the dataset.

### Trend Analysis

* Monthly enrollment trends
* Revenue trends
* Student engagement trends
* Completion trends over time

### Performance Analysis

* Average quiz scores
* Average project grades
* Course completion performance
* Student progress monitoring

### Behavioral Analysis

* Login frequency patterns
* Session duration analysis
* Device usage trends
* Internet quality impact on engagement

### Comparative Analysis

* Students by gender
* Students by employment status
* Students by course level
* Students by course category

---

# VI. Visualization and Dashboard

The dashboard was designed to:

* Provide quick access to important metrics
* Improve decision-making
* Present data visually and interactively
* Simplify interpretation of large datasets

## Dashboard Features

* Interactive filters and slicers
* KPI cards
* Trend analysis charts
* Dynamic visualizations
* User-friendly interface

---

# VII. Insights and Recommendations

## i. Actionable Insights

Based on the data analyzed in the dashboard, several important patterns and trends were identified regarding student engagement, course performance, and learning behavior.

### Insight 1: Students who are more active tend to complete courses more successfully

* The dashboard showed that students with higher login frequency, longer session durations, and more time spent on the platform usually had higher completion rates and better academic performance.

### Insight 2: Advanced courses have lower completion rates

* The analysis showed that advanced-level courses had fewer completed students compared to beginner and intermediate courses.

### Insight 3: Internet quality affects student performance

* Students with poor internet connection quality generally showed lower engagement, shorter session durations, and lower progress percentages.

### Insight 4: Most students use mobile devices for learning

* The dashboard indicated that many students access the platform using mobile phones rather than laptops or tablets.

### Insight 5: Students with higher grades are usually more satisfied

* Students who achieved higher quiz scores and project grades also showed higher satisfaction ratings.

## ii. Data-Driven Recommendations

### Recommendation 1: Encourage students to participate more actively

* The platform can improve student engagement by adding learning reminders, interactive activities, progress tracking features, and reward systems.

### Recommendation 2: Provide additional support for difficult courses

* Advanced courses may include extra tutorials, practice activities, simplified explanations, and academic guidance.

### Recommendation 3: Improve mobile accessibility

* The learning platform should be optimized for smartphones and tablets.

### Recommendation 4: Support students with poor internet connections

* The platform can provide downloadable materials, lower-quality video options, and offline learning support.

### Recommendation 5: Monitor student activity regularly

* Teachers and administrators should regularly monitor student progress, login frequency, quiz scores, and completion status.

## iii. Real-World Interpretation

The findings suggest that student participation and accessibility greatly affect success in online learning environments. Students who are more active and spend more time engaging with lessons are more likely to complete their courses and perform better academically.

The results also show that difficult courses and unstable internet connections can create challenges that may reduce student progress and completion rates. Since many students rely on mobile devices for learning, online platforms should be designed to work efficiently on smartphones and tablets.

Overall, the analysis highlights the importance of student engagement, accessible technology, and supportive learning environments in improving academic performance and online learning experiences.

---

# Prepared By

* Bulotano, Hana Mae P.
* Lobo, Alexander
* Reyes, Jael
* Tisoy, Glory Ann

**Group 7**

# Submitted To

**Ms. Marsha Superio**
Instructor, 7Analytics
