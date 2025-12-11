# Melaka Job Market Analysis & Salary Prediction Using Python

This project explores the **job market landscape in Melaka, Malaysia**, focusing on job availability and salary distribution. Using real job listing data, the analysis uncovers insights that can help **fresh graduates, job seekers, and employers** understand hiring trends and salary expectations.

---

## Key Questions

This analysis aims to answer:

1. Which job categories have the **highest demand** in Melaka?  
2. Which sectors offer the **highest median salaries**?

---

## Tools & Technologies

- **Python**  
- **Pandas & NumPy** – data cleaning & manipulation  
- **Matplotlib & Seaborn** – visualizations  
- **Google Colab** – development environment  

---

## Dataset Description

| Column                  | Description                   |
| ----------------------- | ----------------------------- |
| job_title               | Job position                  |
| company                 | Hiring organization           |
| category                | Main job category             |
| subcategory             | Job sub-category              |
| role                    | Job role type                 |
| type                    | Full-time / Part-time         |
| salary                  | Listed salary range           |
| min_salary / max_salary | Parsed salary fields          |
| avg_salary              | Average salary for prediction |
| Area, state             | Location information          |

---

## Top Job Categories by Vacancy

The categories with the highest number of vacancies in Melaka are:

1. **Accounting**  
2. **Manufacturing, Transport & Logistics**  
3. **Administration & Office Support**  

---

## Relationship Between Job Count & Salary

A scatter plot analysis shows:

1. Categories with **high job demand** do not always offer **high salaries**.  
2. Specialized categories with **fewer jobs** often provide **higher salary opportunities**.  
3. This helps job seekers align expectations between **job availability** and **salary potential**.

---

## Conclusion

1. **Accounting, Administration, and Manufacturing** are the highest-demand categories in Melaka.  
2. Some categories offer **higher salaries but fewer opportunities**, such as **Engineering and IT**.  
3. Job seekers—especially fresh graduates—should **balance job availability with salary goals**.  
4. The salary prediction model provides a foundation for **job recommendation systems or salary benchmarking tools**.
