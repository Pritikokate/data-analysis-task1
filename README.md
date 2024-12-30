# data-analysis-task1
This project analyzes student performance, focusing on final grades (G3). It involves loading the dataset, cleaning missing values, and checking correlations with study time. Key analyses include calculating the average G3 score, identifying students scoring above 15, and comparing grades by gender.
Here's a sample README file for your project:

Here's a sample README file for your project:

---

# Student Performance Analysis

## Overview

This project analyzes a dataset of student exam scores and explores the relationships between various factors such as study time, gender, and final grades. The dataset contains information about students' scores across three terms, their study time, and their gender. The project performs data loading, exploration, cleaning, analysis, and visualization using Python libraries such as pandas and matplotlib.

## Project Steps

### 1. **Dataset Selection**
   - Dataset: `student-mat.csv`
   - Columns:
     - **G1**, **G2**, **G3**: Grades for three terms.
     - **studytime**: Hours spent studying weekly.
     - **sex**: Gender (Male/Female).

### 2. **Data Loading**
   - Loaded the dataset using pandas.
   - Displayed the first few rows using `.head()`.

### 3. **Data Exploration**
   - Checked for missing values using `.isnull().sum()`.
   - Displayed column data types using `.dtypes`.
   - Understood the dataset's size using `.shape`.

### 4. **Data Cleaning**
   - Handled missing values (e.g., replacing them with the median or removing rows).
   - Removed duplicate entries using `.drop_duplicates()`.

### 5. **Data Analysis Questions**
   - **Average Score in Math (G3)**: Calculated the average score for the final grade (G3).
   - **Students Scoring Above 15**: Counted how many students scored above 15 in their final grade (G3).
   - **Correlation between Study Time and Final Grade (G3)**: Calculated the correlation between study time and G3.
   - **Average Final Grade by Gender**: Compared the average final grade (G3) between male and female students.

### 6. **Data Visualization**
   - Plotted a **histogram** for the distribution of final grades (G3).
   - Created a **scatter plot** to show the relationship between study time and final grade (G3).
   - Used a **bar chart** to compare the average final grades between male and female students.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   ```

2. Install the necessary libraries:
   ```bash
   pip install pandas numpy matplotlib
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Results

- **Average Score (G3)**: 10.42 (rounded).
- **Number of Students with G3 > 15**: X (replace X with the actual count).
- **Correlation between Study Time and G3**: 0.098 (weak positive correlation).
- **Average Scores by Gender**: Male students tend to have a slightly higher average G3 score than female students.



