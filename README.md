# **Power BI Dashboard for Healthcare Patient Waiting Lists**

## Introduction
This project focuses on creating a comprehensive Power BI dashboard to monitor and analyze patient waiting lists, covering both inpatient and outpatient data. The dashboard provides insights into historical trends, specialty-level analysis, and age profile analysis.

## Background
The primary objective of this dashboard is to help healthcare administrators track the current status of patient waiting lists, analyze historical trends, and conduct in-depth specialty and age profile analysis. The dashboard was developed following a structured process that includes data collection, transformation, and visualization.

## Dataset
- **Source**: [Dataset](https://github.com/noblebenn/powerbi/tree/72524c17cc37aa1d304538f284a93333a140c701/Patient%20Wait%20List/Data)
- **Type**: Healthcare data from 2018 to 2021
- **Categories**:
  - **Inpatient**: Patients admitted for treatment.
  - **Outpatient**: Patients treated without admission.

## Steps Followed in Creating the Dashboard

### Step 1: Requirement Gathering
1. **Understand Business Objectives**
   - Conducted meetings with stakeholders to outline goals and objectives.
   - Focused on key questions related to patient waiting list trends and specialty analysis.

2. **High-Level Data Study**
   - Analyzed data sources, column descriptions, data types, and data quality.

3. **Define Scope**
   - Finalized key metrics, KPIs, and scope of the dashboard, ensuring a 20% buffer in deadlines.

### Step 2: Data Collection
- Used Power BI to collect data from multiple sources, including Excel files.
- Leveraged the folder connector to collate data efficiently.

### Step 3: Data Transformation
- Loaded and appended inpatient and outpatient data into Power BI.
- Performed data type checks and ensured data integrity.
- Created a mapping table for specialty categorization.

### Step 4: Data Visualization Blueprint
- **Summary Page**:
  - Visuals: Card for total waiting list, donut chart for average waiting list, column chart for age profile, grid for specialty analysis, and monthly trend chart.
  
- **Detail Page**:
  - Grid view with user interaction filters.

### Step 5: Designing the Dashboard
- Set up the grid and alignment in Power BI.
- Implemented visuals such as cards, donut charts, stacked column charts, and matrix grids.
- Added toggle buttons for switching between average and median waiting lists.

### Step 6: Adding Interactivity and Navigation
- Created dynamic measures for titles and metric toggling.
- Added tooltips for additional insights.
- Included navigation buttons for seamless transition between pages.

### Step 7: Testing
- Conducted thorough testing to verify data accuracy, interactivity, and visual coherence.

### Step 8: Sharing
- Implemented role-level security and published the dashboard to Power BI services.
- Shared the dashboard with stakeholders.

## Analysis
- **Inpatient vs Outpatient Trends**: The dashboard clearly highlights the differences and trends between inpatient and outpatient waiting lists over time.
- **Specialty Analysis**: Allows for detailed analysis at the specialty level, identifying areas with higher waiting times.
- **Age Profile**: Provides insights into the age distribution of patients on the waiting list.

### Visualizations
- **Total Waiting List**: Displayed as a card visual showing the current month's total compared to the previous year.
- **Average Waiting List**: Visualized using a donut chart, providing a breakdown by patient type.
- **Age Profile Analysis**: A column chart depicting the age distribution of patients.
- **Specialty Analysis**: A matrix showing the top five specialties with the highest average waiting lists.

## What I Learned
- **Data Preparation**: The importance of accurate data transformation and the creation of a unified data table.
- **Visualization Techniques**: How to effectively use Power BI's visual tools to present data in an informative and engaging way.
- **Interactivity**: Implementing dynamic features to enhance user experience and interactivity within the dashboard.

## Conclusion
This dashboard serves as a powerful tool for healthcare administrators, providing a clear view of patient waiting lists and enabling informed decision-making. The process of building this dashboard has reinforced my skills in data analysis, visualization, and dashboard design.

## Repository Structure
- **Dataset**: [Dataset](https://github.com/noblebenn/powerbi/tree/72524c17cc37aa1d304538f284a93333a140c701/Patient%20Wait%20List/Data)
- **Dashboard File**: [Power BI File](https://github.com/noblebenn/powerbi/blob/c1c9fbf95cfad802e82df1c2962a4dc839c9c90d/Patient%20Wait%20List/project.pbix)
- **Preview pdf of the Dashboard**:[Pdf Preview](https://github.com/noblebenn/powerbi/blob/b9777dd863c2136236769454b417fac21d97e9af/Patient%20Wait%20List/Wait%20List%20Comparison.pdf)
- **Documentation**: This README file and any additional documentation.

## How to Use
1. Download the dataset and Power BI file from the links provided.
2. Open the Power BI file and connect to the dataset.
3. Explore the dashboard to gain insights into patient waiting lists.

---

Feel free to customize the links and any other specifics as needed. This format should effectively communicate the process and outcomes of your Power BI dashboard project.

