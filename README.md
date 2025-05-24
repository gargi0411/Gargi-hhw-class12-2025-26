#  Class 12A Performance Dashboard

**Created by:** Gargi  
**Platform:** JupyterLab (Python 3 - ipykernel)  
**Last Updated:** 4 hours ago  
**Class:** 12A

---

##  Project Overview

This interactive data visualization project analyzes the **academic performance of Class 12A students** across multiple subjects using engaging visual tools. It combines grouped bar graphs and pie charts to reveal student-wise and subject-wise insights in a clear and colorful format.

Whether you're a teacher, student, or curious observer, this dashboard helps you **see the story behind the scores**.

---

##  Visual 1: Grouped Bar Chart — Student-wise Performance by Subject

This chart presents a side-by-side comparison of students' marks across all subjects.

### Key Features:
- **X-Axis**: Displays the names of students.
- **Y-Axis**: Shows the marks scored (0–100).
- **Bar Colors**: Each subject is uniquely color-coded.
- **Grouped Bars**: All subjects for each student are grouped together.
- **Legend**: Maps each color to its subject for easy reference.
- **Rotation**: Student names are rotated for better readability.

 **Why It Matters:**  
Quickly identify which students are excelling overall or in specific subjects. A powerful tool for spotting trends and gaps.

---

##  Visual 2: Pie Charts — Grade Distribution per Subject

This section includes individual pie charts for each subject, showing how grades are distributed among students.

###  How It Works:
1. A custom `assign_grade()` function maps numeric marks to letter grades:
   - **A+**: 90 and above  
   - **A**: 80–89  
   - **B**: 70–79  
   - **C**: 60–69  
   - **D**: 40–59  
   - **F**: Below 40

2. Marks are cleaned and converted to numeric values.
3. Each student’s grade is determined.
4. Grade counts are visualized in vibrant pie charts.

###  Insights Offered:
- See which subjects have the most top performers.
- Spot subjects where students may need extra support.
- Gain a holistic view of grade distribution at a glance.

---

##  Files Included

| Filename                           | Description                                                  |
|------------------------------------|--------------------------------------------------------------|
| `grouped_bar_graph.ipynb`          | Notebook for visualizing student-wise performance by subject |
| `grade_distribution_pie_charts.ipynb` | Notebook for generating pie charts for grade analysis      |
| `report.pdf`                       | Project summary created in MS Word and exported as PDF       |

---

##  Tools & Technologies

- **JupyterLab** with Python 3
- **Libraries**: `pandas`, `matplotlib`
- **Markdown** for documentation
- **Data Visualization** for performance insights

---

