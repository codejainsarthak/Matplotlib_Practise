# Student Performance Analysis using Matplotlib

## Project Overview

This project analyzes student performance based on study habits using Python, Pandas, and Matplotlib. It focuses on understanding how factors like study hours and subjects impact student marks through data visualization.

---

## Dataset Description

The dataset contains the following columns:

- Student – Student name/ID
- Study_Hours – Number of hours studied per day
- Sleep_Hours – Daily sleep duration
- Marks – Exam scores
- Subject – Subject category

---

## Objectives

- Analyze relationship between study hours and marks
- Identify top-performing and underperforming students
- Compare average marks across subjects
- Visualize data using different types of charts

---

## Visualizations Used

### Line Plot

Displays Marks vs Students and highlights the top scorer.

### Bar Chart

Shows average marks per subject.

### Histogram

Displays distribution of study hours.

### Scatter Plot

Shows relationship between study hours and marks and helps identify correlation.

### Dashboard (Subplots)

All visualizations are combined into a 2x2 layout using figsize and tight_layout for better readability.

---

## Key Insights

- There is a strong positive correlation between study hours and marks
- Students who study more tend to score higher
- Some variation exists, indicating performance is also affected by other factors
- Students with similar study hours can still have different outcomes, suggesting efficiency plays a role

---

## Skills Demonstrated

- Data manipulation using Pandas
- Data visualization using Matplotlib
- Use of subplots, figsize, groupby
- Implementation of histogram, scatter, bar, and line plots
- Analytical thinking and insight extraction

---

## Tech Stack

- Python
- Pandas
- Matplotlib

---

## How to Run

1. Install required libraries:

   ```bash
   pip install pandas matplotlib
   ```

2. Run the Python script:

   ```bash
   python analysis.py
   ```

---

## Future Improvements

- Use a larger and more realistic dataset
- Perform advanced analysis such as correlation heatmaps and regression
- Build an interactive dashboard using tools like Plotly or Power BI

---

## Conclusion

This project demonstrates how data visualization techniques can be used to extract meaningful insights and build a strong foundation for data analysis.
