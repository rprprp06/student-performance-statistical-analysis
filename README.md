# Student Performance Statistical Analysis

## Overview
This project performs a complete statistical analysis on the Student Performance (Math) dataset using Python and Pandas.

The project demonstrates:
- File handling with exception handling
- Data exploration and filtering
- Missing value handling
- Feature engineering
- Statistical calculations
- Group-wise analysis
- Report generation

---

## Dataset Information
- Dataset: Student Performance (Math)
- Rows: 395
- Columns: 33

The dataset contains:
- Student demographic details
- Family background
- Study habits
- School support information
- Grades (G1, G2, G3)
- Absences and health details

Dataset Source:
https://archive.ics.uci.edu/dataset/320/student+performance

---

## Features Implemented

### 1. File Handling
- try-except blocks
- FileNotFoundError handling
- PermissionError handling

### 2. Data Exploration
- Display first and last rows
- DataFrame information
- Conditional filtering using loops

### 3. Missing Value Handling
- Manual mean and median calculation
- User-defined functions

### 4. Feature Engineering
Created new columns:
- StudyEfficiency
- GradeImprovement
- FamilySupportScore

### 5. Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Minimum
- Maximum

Using:
- Loops
- Lists
- Tuples
- Recursion
- Pandas functions

### 6. Group Analysis
Performed analysis based on:
- School
- Gender
- Family education background

### 7. Final Report
Generated:
student_performance_analysis_report.txt

---

## Technologies Used
- Python
- Pandas
- NumPy
- File Handling
- Functions
- Recursion
- Dictionaries
- Sets
- Lists and Tuples

---

## Project Structure

```bash
student-performance-statistical-analysis/
│
├── student_analysis.py
├── student-mat.csv
├── student_performance_analysis_report.txt
├── README.md
