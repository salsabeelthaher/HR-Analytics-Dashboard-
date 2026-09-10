<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>HR Analytics Dashboard</title>
</head>
<body>

<h1>HR Analytics Dashboard</h1>

<p>An interactive Business Intelligence dashboard built to analyze and visualize key HR metrics across an organization of <strong>4,881 employees</strong>. The dashboard consolidates workforce data  demographics, attrition, compensation, education, location, and performance indicators  into a single, filterable view that supports data-driven HR decision-making.</p>

<p>
  <img src="./dashboard-screenshot.png" alt="HR Analytics Dashboard">
</p>

<h2>Overview</h2>
<p>The dashboard provides a 360° view of the workforce, combining high-level KPI cards with department-level and category-level breakdowns. It is designed to help HR teams and management quickly identify attrition trends, monitor training and salary metrics, and understand workforce composition by department, education, gender, and location.</p>

<h2>Key Metrics (KPI Cards)</h2>
<table>
  <thead>
    <tr><th>Metric</th><th>Value</th></tr>
  </thead>
  <tbody>
    <tr><td>Total Employees</td><td>4,881</td></tr>
    <tr><td>Average Age</td><td>35.13</td></tr>
    <tr><td>Average Salary</td><td>1.50M</td></tr>
    <tr><td>Average Experience</td><td>9.73 years</td></tr>
    <tr><td>Average Training Hours</td><td>30.19 hrs</td></tr>
    <tr><td>Female Employees</td><td>2,448</td></tr>
    <tr><td>Male Employees</td><td>2,433</td></tr>
  </tbody>
</table>

<h2>Dashboard Components</h2>
<ul>
  <li><strong>Count of Employee ID by Department</strong> — Horizontal bar chart ranking headcount across Marketing, IT, Finance, Operations, HR, and Sales.</li>
  <li><strong>Attrition Rate by Department</strong> — Horizontal bar chart showing attrition counts per department, highlighting HR and Marketing as the highest.</li>
  <li><strong>Count of Employee ID by Attrition</strong> — Donut chart summarizing overall attrition split (15.02% attrited vs. 84.98% retained).</li>
  <li><strong>Count of Employee ID by Promotion</strong> — Donut chart showing the proportion of employees promoted (11.37%) vs. not promoted (88.63%).</li>
  <li><strong>Average of AttendancePct (Min/Max)</strong> — Gauge chart displaying average attendance percentage (87.21 out of 100).</li>
  <li><strong>Avg Experience by Gender</strong> — Side-by-side comparison of average years of experience for male (9.84) and female (9.62) employees.</li>
  <li><strong>Count of Employee ID by Education</strong> — Column chart segmenting headcount by education level (MBA, M.Tech, B.Tech, Masters, Bachelors).</li>
  <li><strong>Count of Employee ID by Location</strong> — Column chart showing employee distribution across major cities (Bengaluru, Delhi, Hyderabad, Chennai, Pune, Mumbai).</li>
  <li><strong>Count of Employee ID by Job Satisfaction</strong> — Column chart displaying employee counts across job satisfaction rating levels (1–5).</li>
</ul>

<h2>Filters / Slicers</h2>
<ul>
  <li><strong>Date of Joining</strong> — Date range slider (1/1/2016 – 2/17/2026)</li>
  <li><strong>Department</strong> — Finance, HR, IT, Marketing, Operations, Sales</li>
  <li><strong>Gender</strong> — Female, Male</li>
</ul>
<p>These slicers allow interactive cross-filtering of all visuals based on hire date, department, and gender.</p>

<h2>Dataset</h2>
<p>The dashboard is powered by an employee-level dataset (<code>HR_Analytics_Dataset.csv</code>) with the following fields:</p>
<p><code>EmployeeID</code>, <code>Department</code>, <code>Gender</code>, <code>Age</code>, <code>DateOfJoining</code>, <code>Salary</code>, <code>Experience</code>, <code>TrainingHrs</code>, <code>Education</code>, <code>Location</code>, <code>JobSatisfaction</code>, <code>Attrition</code>, <code>Promotion</code>, <code>AttendancePct</code></p>

<h2>Tools Used</h2>
<ul>
  <li><strong>Power BI</strong> — dashboard design, DAX measures, and interactive visuals</li>
  <li><strong>CSV / Excel</strong> — source data preparation</li>
</ul>

<h2>Insights</h2>
<ul>
  <li>Attrition sits at roughly <strong>15%</strong> overall, with HR and Marketing showing the highest attrition counts.</li>
  <li>Only <strong>11.37%</strong> of employees have been promoted, suggesting limited internal mobility.</li>
  <li>Average attendance (<strong>87.21%</strong>) indicates generally consistent workforce presence.</li>
  <li>Experience levels are fairly balanced between genders, with male employees averaging slightly higher tenure.</li>
</ul>

<h2>Author</h2>
<p>Add your name, university, and course/project details here (e.g., <em>Business Information Technology, The University of Jordan</em>).</p>

<h2>License</h2>
<p>Add a license of your choice (e.g., MIT) if this repository is public.</p>

</body>
</html>
