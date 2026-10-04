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
-
  <img width="1312" height="733" alt="Screenshot 2026-10-04 213236" src="https://github.com/user-attachments/assets/6aa69a60-be24-478d-8251-7f07ed37a371" />

- <img width="1328" height="735" alt="Screenshot 2026-10-04 213300" src="https://github.com/user-attachments/assets/6ba234b4-e089-4e9a-89ed-35023ce641d4" />

- <img width="1327" height="741" alt="Screenshot 2026-10-04 213323" src="https://github.com/user-attachments/assets/4a66b4be-c599-4849-bf4a-be295359c7ef" />

- <img width="1337" height="732" alt="Screenshot 2026-10-04 213343" src="https://github.com/user-attachments/assets/9578e3f8-f080-4b5e-849c-8fc9732cba12" />


## Key findings
- The overall attrition rate is 16.1%, with Sales Representative the highest at 39.8%.
- Employees who work overtime leave at a higher rate 30.5% vs 10.4%.
- Attrition is highest among employees with 0-1 year at the company almost 35%.



