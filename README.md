# 🔄 Which Employees Are Leaving?
## Table of Contents
[Dataset](#dataset) | [Purpose](#purpose) | [Methods](#methods) | [Procedure](#procedure) | [Findings](#findings) | [Recommendations](#recommendations) | [Takeaways](#takeaways)

## Dataset
I downloaded the [IBM HR Attrition dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data) from Kaggle. This dataset, created by data scientists at IBM, contains 1,470 records and is designed to simulate realistic employee data.

## Purpose
I chose a dataset focused on attrition, as employee turnover is a prominent problem that organizations attempt to tackle. Studying attrition data can help organizations identify associations with turnover to improve retention and support workforce planning to anticipate future staffing needs.

## Methods
I aimed to compile descriptive summaries of the dataset, then visualize these statistics through various charts and slicers to create an interactive dashboard. This project was completed entirely in Excel, as it is a versatile application that can both analyze and visualize data. Rather than applying more complex methods like logistic regression, I opted for a descriptive approach that is easier to communicate to stakeholders. That is why this project is titled “**Which** Employees Are Leaving?” instead of “**Why** Are Employees Leaving?”. My goal is to highlight patterns rather than make predictions. Therefore, this data analysis is descriptive, not predictive.

## Procedure
View my [Excel file](https://github.com/Kathleen-D/Which-Employees-Are-Leaving/blob/a3db0ffbab49d397eee924d4faf38289e2b2951c/IBM%20HR%20Attrition%20Analysis.xlsx) to reference my procedure. To start, I converted the raw dataset into a structured format to prepare it for analysis, while keeping the raw and prepared datasets in separate locked tabs to maintain data integrity. Then, I selected several attrition factors to explore and created a separate tab for each of them. For every factor, I generated a pivot table with descriptive summaries and used it to build a corresponding chart. To enhance chart readability, I created additional columns in the prepared dataset to convert numerical scale values into descriptive text labels (e.g., 1 = "Low," 4 = "Very High"). These charts were then transferred into a dashboard tab, which I enhanced with a clear title, color formatting, and slicers to make the visualization intuitive and interactive. 

<table>
  <tr>
    <td>Raw Data</td>
    <td>Prepared Data</td>
    <td>Additional Columns</td>
  </tr>
  <tr>
    <td><img src="Other Images/Raw Data.png" width="328"></td>
    <td><img src="Other Images/Prepared Data.png" width="328"></td>
    <td><img src="Other Images/Additional Columns.png" width="328"></td>
  </tr>
</table>
<table align="center">
  <tr>
    <td>Dashboard</td>
  </tr>
  <tr>
    <td><img src="Other Images/Dashboard.png" width="438"></td>
  </tr>
</table>

## Findings
My dashboard was designed as a standalone deliverable, with key findings and recommendations for stakeholder presentation and decision-making. I chose to analyze 6 factors in relation to work attitudes and context. Attitudinal factors in conjunction with contextual factors capture both the emotional and structural aspects of the work experience, which offers the bigger picture of attrition. Job satisfaction, environment satisfaction, relationship satisfaction, job involvement, work-life balance, and job level were examined. To explore whether these factors differ across groups, I also used department and gender as slicers. The entirety of my findings are below. 

1. **Job Satisfaction**
- Employees who are more satisfied with their jobs showed lower observed attrition rates; HR employees showed especially high attrition rates when their job satisfaction was low.
- Men showed higher attrition rates when their job satisfaction was low, while women showed higher attrition rates when their job satisfaction was medium.
<table align="center">
  <tr>
    <td>Job Satisfaction Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Job Satisfaction Chart.png" width="438"></td>
  </tr>
</table>

2. **Environment Satisfaction**
- The more employees are satisfied with their work environment, the lower their observed attrition rates.
- Women in HR showed very high attrition rates when their environment satisfaction was low to medium, with observed turnover rates of 84% at low satisfaction and 100% at medium satisfaction.
<table align="center">
  <tr>
    <td>Environment Satisfaction Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Environment Satisfaction Chart.png" width="438"></td>
  </tr>
</table>

3. **Relationship Satisfaction**
- Employees who are more satisfied with their work relationships showed lower observed attrition rates.
- In R&D and sales, very high relationship satisfaction is associated with lower turnover for employees; in HR, however, even very high relationship satisfaction was not associated with lower attrition for employees.
<table align="center">
  <tr>
    <td>Relationship Satisfaction Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Relationship Satisfaction Chart.png" width="438"></td>
  </tr>
</table>

4. **Job Involvement**
- The more employees are involved with their job, the lower their observed attrition rates.
- Across all departments, sales employees showed the highest attrition rates when job involvement was low.
<table align="center">
  <tr>
    <td>Job Involvement Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Job Involvement Chart.png" width="438"></td>
  </tr>
</table>

5. **Work-Life Balance**
- Employees who have more work-life balance showed lower observed attrition rates.
- Men showed lower attrition rates when their work-life balance was very high, while women showed notable attrition rates even when their work-life balance was very high.
<table align="center">
  <tr>
    <td>Work-Life Balance Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Work-Life Balance Chart.png" width="438"></td>
  </tr>
</table>

6. **Job Level**
- The higher their job level, the lower employees' observed attrition rates.
- Employees at job levels 1 and 3 showed higher attrition rates than those at other job levels.
<table align="center">
  <tr>
    <td>Job Level Chart</td>
  </tr>
  <tr>
    <td><img src="Charts/Job Level Chart.png" width="438"></td>
  </tr>
</table>

Together, these 6 factors converge on a critical question: ***Which employees had the highest observed attrition rates, and where should the organization intervene first?***

## Recommendations
I would propose these recommendations to stakeholders. Each recommendation below is grounded in one or more of the findings above, with particular attention to the factors most consistent with attrition risk. This is simply a starting point, however, further analysis may be necessary to translate these into actionable strategies.
- **Prioritize the HR department.** Targeted stay interviews and a workload audit within HR may be warranted before other departments. HR employees showed consistently high attrition rates across nearly every factor examined, making it the department most urgently in need of intervention.
- **Invest in entry and mid-level employee development.** Structured career pathing, transparent promotion criteria, and mentorship programs may reduce the perception that growth opportunities are limited. Employees at job levels 1 and 3 showed the highest observed attrition rates among all job levels, suggesting that stagnation or unclear advancement pathways may be associated with early exits.
- **Strengthen job involvement**. Redesigning roles to include more autonomy, meaningful tasks, and clear impact may increase involvement, which in turn, is associated with higher retention. Job involvement was one of the most consistent indicators of attrition across all departments, particularly in sales where low involvement was associated with the highest observed attrition rates.

## Takeaways
This project tested my foundational knowledge in the quantitative side of I-O psychology, and reinforced that good analysis is as much about communication as it is about the numbers. These are several lessons I am carrying forward.
- **Descriptive methods can be powerful on their own.** Simpler methods forced clearer thinking about what I was actually claiming. 
- **Data integrity is the starting point.** Locking the raw and prepared datasets into separate tabs from the start saved me from several potential setbacks. It is especially helpful when you need to retrace your steps.
- **Design is part of the analysis.** Converting numeric scale values into text labels (e.g., 1 = "Low," 4 = "Very High") and adding interactive slicers were not simply aesthetic choices. They changed how accessible the findings were to a non-technical audience.
- **Disaggregation reveals much more.** Some of the most interesting findings, like the 100% turnover rate among women in HR at medium environment satisfaction, were found when I broke the data down by department and gender. Surface-level analysis would have missed them entirely.
- **A focused research question is great for your audience.** Narrowing the focus to which employees are leaving, rather than why, kept the findings clear and interpretable.

My next project moves from describing who left to predicting who is at risk of burning out, using Python and machine learning. This is a shift from descriptive to predictive analytics, and from people data to the intersection of work and technology. What I-O psychology brings to this kind of work is not just domain knowledge, it is scientific discipline. Knowing whether a measure is valid before modeling it, distinguishing practical significance from statistical significance, and treating a predictive model as an organizational intervention rather than a technical artifact make findings worth acting on. That combination of analyst, consultant, and scientist is what I am building toward.
