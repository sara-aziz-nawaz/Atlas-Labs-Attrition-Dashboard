# Atlas Labs Employee Attrition Dashboard (Power BI)

An HR analytics report built in Power BI to track headcount, employee demographics, performance and attrition.

## Business questions
- How many employees are active vs. inactive, and what is the attrition rate?
- Which departments, job roles and tenure groups lose the most people?
- Does overtime or business travel relate to attrition?
- How do satisfaction and performance ratings change over time for each employee?

## Report pages
1. **Overview:** total, active and inactive employees, attrition rate, hiring trends, and active employees by department and job role.
2. **Demographics:** employees by age band, gender, marital status, and ethnicity with average salary.
3. **Performance Tracker:** pick an employee by name to see start date, last and next review, and job satisfaction, relationship satisfaction, self rating, work-life balance, manager rating and environment satisfaction by year.
4. **Attrition:** attrition rate by department and job role, hire date, travel frequency, overtime requirement and tenure.

## Data model
Star schema with a fact table (`FactPerformanceRating`) and dimensions (`DimEmployee`, `DimDate`, `DimEducationLevel`, `DimRatingLevel`, `DimSatisfiedLevel`), plus a separate `_Measures` table holding the DAX measures (for example Total Employees, Active Employees, % Attrition Rate).

## Tools
Power BI Desktop, Power Query, DAX, data modelling.

## Screenshots
Add one screenshot per page here, for example:
- `screenshots/overview.png`
  <img width="1312" height="733" alt="Screenshot 2026-10-04 213236" src="https://github.com/user-attachments/assets/6aa69a60-be24-478d-8251-7f07ed37a371" />

- `screenshots/demographics.png`
- `screenshots/performance_tracker.png`
- `screenshots/attrition.png`

## Key findings
[Add 2-3 findings from your dashboard, e.g. which department has the highest attrition, and the effect of overtime.]
Add Atlas Labs Dashboard

## Data
[State the source, e.g. public sample HR dataset, course dataset, or synthetic data. Only upload data you are allowed to share.]
