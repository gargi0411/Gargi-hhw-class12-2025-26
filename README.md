#  Class 12A Performance Dashboard

** Created by:** Gargi Naroliya  
** Class:** 12A  
** Subject:** Information Practices  
** Subject Code:** 065  
** Platform:** JupyterLab (Python 3 - ipykernel)

---

##  Project Overview

This interactive data visualization project analyzes the **academic performance of Class 12A students** across multiple subjects using engaging datamanegment and visual tools.

It combines **grouped bar graphs** and **pie charts** to reveal student-wise and subject-wise insights in a clear, colorful, and meaningful way.

---

##  Visual 1: Grouped Bar Chart — Student-wise Performance by Subject

A side-by-side comparison of marks scored by each student in all subjects.

### 🔍 Key Features:
- **X-Axis**: Displays student names
- **Y-Axis**: Marks scored (0–100)
- **Color-coded Bars**: Each subject has a unique color
- **Grouped Bars**: All subjects for a student shown together
- **Legend**: Maps each color to a subject
- **Rotated Labels**: For clear readability

 **Why Its Important:**  
Easily identify overall toppers, subject strengths, and areas for improvement — all at a glance.

---

## Visual 2: Pie Charts — Grade Distribution per Subject

Each subject is analyzed using a **pie chart** that shows how grades are distributed among students.

###  How It Works:
1. A custom Python function `assign_grade()` maps marks to letter grades:
   - **A+**: 90 and above  
   - **A**: 80–89  
   - **B**: 70–79  
   - **C**: 60–69  
   - **D**: 40–59  
   - **F**: Below 40

2. Marks are cleaned and converted into numeric form.
3. Grades are computed and visualized as colorful pie charts.

###  Insights Offered:
- Spot high-achieving subjects
- Identify subjects where students need more support
- Get a snapshot of overall grade trends

---

##  Files Included

| Filename                              | Description                                                      |
|---------------------------------------|------------------------------------------------------------------|
| `Gargi class12A.ipynb`                | Notebook to visualize student-wise performance by subject        |
|                                       | and generate pie charts for grade analysis                       |
| `report.pdf`                          | Summary of the project created in MS Word, exported as a PDF     |
| `README.md`                           | Project overview and documentation (this file)                   |
| `screenshots/`                        | Folder containing images of graph outputs                        |

---

## 🛠️ Tools & Technologies Used

- **JupyterLab** with Python 3
- **Python Libraries**:  
  - `pandas` (for data handling)  
  - `matplotlib.pyplot` (for plotting)
- **Markdown** (for documentation)
- **Data Visualization** (to derive and display insights)

---

##  Conclusion

This project demonstrates how programming and data science can simplify academic evaluation by combining **automation, logic, and storytelling through visuals**.

It’s a small step into the world of **data-driven education** — turning numbers into narratives.

---
