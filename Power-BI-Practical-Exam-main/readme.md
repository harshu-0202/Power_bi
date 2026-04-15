# 📊 Student Performance & Behavior Analysis Dashboard (Power BI)

## 📌 Project Overview

This Power BI project provides a comprehensive analysis of student
performance, attendance, and behavioral patterns. The dashboard
integrates multiple datasets to uncover insights that help educators
monitor academic progress, identify at-risk students, and improve
overall decision-making.

## 🎯 Objectives

-   Analyze student academic performance across subjects and exams\
-   Track attendance trends and identify irregularities\
-   Monitor behavioral records for better student management\
-   Provide a unified dashboard for data-driven insights

## 🗂️ Datasets Used

1.  **Students Dataset**
    -   Student ID, Name, Gender\
    -   Class and Section
2.  **Attendance Dataset**
    -   Student ID, Date\
    -   Attendance Status (Present/Absent)\
    -   Reason for absence
3.  **Scores Dataset**
    -   Subject-wise scores\
    -   Exam types (Mid Term, Final Exam, Unit Test)\
    -   Term-wise performance
4.  **Behavior Dataset**
    -   Behavioral incidents\
    -   Remarks and notes

## 🔗 Data Model

The datasets are connected using **StudentID** as the primary key: -
One-to-many relationships between Students and other tables\
- Centralized student dimension table\
- Fact tables: Attendance, Scores, Behavior

## 📈 Key Features of Dashboard

-   📊 **Performance Analysis**
    -   Subject-wise score distribution\
    -   Term-wise performance trends\
    -   Top and low-performing students
-   📅 **Attendance Insights**
    -   Attendance percentage by student/class\
    -   Monthly attendance trends\
    -   Absence patterns
-   ⚠️ **Behavior Monitoring**
    -   Frequency of behavioral incidents\
    -   Student-wise behavior tracking
-   🧑‍🎓 **Student Overview**
    -   Individual student performance summary\
    -   Combined view of attendance, scores, and behavior

## 📊 Key Metrics

-   Average Score (%)\
-   Attendance Rate (%)\
-   Number of Behavioral Incidents\
-   Performance by Subject & Term

## 🛠️ Tools & Technologies

-   Power BI Desktop\
-   Excel\
-   Data Modeling

## 📷 Dashboard Preview

![Dashboard](Dashboard.png)
![Dashboard2](Dahboard2.png)
![Preview](Preview.png)
![Photo](Photo.png)

## 🚀 How to Use

1.  Download the `.pbix` file\
2.  Open in Power BI Desktop\
3.  Refresh data\
4.  Explore dashboard

## 💡 Insights Generated

-   Low attendance impacts performance\
-   Behavior affects academic outcomes\
-   Subject strengths & weaknesses identified\
-   Term-wise performance trends

## 📁 Repository Structure

    ├── Power BI- Exam.pbix
    ├── Attendance.xlsx
    ├── Students.xlsx
    ├── Behavior.xlsx
    ├── Scores.xlsx
    └── readme.md
    └── Dashboard.png
    └── Dashboard2.png
    └── Preview.png
    └── Photo.png 
    
    
