# HEALTHCARE DATA PATIENT WAIT LISTS ANALYS IS WITH POWER-BI

This data analysis project on Power BI aimed at providing insight into the patient waiting list of an healthcare facility from the year 2018 - 2021. By analysing various aspect of the Patient data, we seek to identify trends in regards to inpatient and outpatient waiting list and patient day cases, make data driven understanding of the healthcare's performance and ultimately provide meaningful insights.


In this era of modern healthcare, managing patient waitlists for inpatient and outpatient is crucial. This project dives into the world of healthcare data visualization, exploring a Power BI dashboard designed to optimize patient waitlists. This project helps healthcare providers gain vital information to streamline patient flow, allocate resources effectively, and ultimately enhance the quality of care provided which will ultimately leading to improved healthcare outcomes and a better patient experience.

![image](https://github.com/Nwarache/HEALTHCARE-DATA-PATIENT-WAIT-LISTS-ANALYSIS-WITH-PIOWER-BI-DASHBOARD./assets/161589821/833630b5-0b2a-4297-b71d-07565ea42190)

Dataset term definations :
Inpatient.
Outpatient.
Daycase

Inpatiennt : A patient who stays in a hospital while undergoing treatment and getting medical attention.
Outpatient : A patient who receives medical attention or treatment without being admitted to a hospital.
Daycase : A patient who receives medical care and goes home the same day, but needs more time for recovery at the hospital.

## DATA SOURCE:

This dataset used for thiis project consists of two types of data categories. The data source is Kaggle, encompassing patient admission and release timestamps, age, adult status, specialty visits (like cardiology, general surgery, psychology), and duration of stays. These datasets were split into two separate tables for inpatient and outpatient records from 2018 to 2021, total number of rows and columns in the dataset after appending was 182,136 and 9 respectively.  The Inpatient and Outpatient data is the primary dataset used for this analysis. The Inpatient and Outpatient data csv folder files contains detailed information about each category of these patients in relation to the Health care facility.


## Analysis : 

I posed several pivotal questions to guide the exploration of the dataset. Exploratory data analysis: (EDA) Involved exploring the seperate data set folders to answer key questions like:

How does the current year’s total waitlist compare to the previous year?
How many Patient falls under which Case Type?
How does the duration of hospital stays vary across different age groups of patients?
What are the top 5 wait lists by specialty?
What are the monthly trends observed among patients with different case types?


DATA ANALYSIS:

This includes some interesting data cleaning and appending processes using Power Query on Power BI.

## DASHBOARD DEVELOPMENT PROCESS

Steps :
Requirement gathering.
Data collection and cleaning.
Transformation and modelling.
Table Connections.
Data Visualizations blueprint.
Dashbaord Layput and design.
Interactivity and Navigation.
Testing.
Sharing and insights.
Maintainance and Refresh.


### Requiremnt gathering phase :

This first step begins with Identifying with the stakeholders and establishing a point of contact, understanding the actual problem and what objective that is set to be achieved. Understanding the stakeholders help in clarifying doubts, asking relevant questions and getting relevant information on how the details, information and insights on the dashboard shoiuld look like. It basically saves a lot of time and creates room to be on the same page with the stakeholders. Requirement gatheing is simply identifying and understanding set business objectives or goals, getting the data source, column discriptions, data types, volume and data quality. Requiremt gathering creates an avenue for scope definations, key performace indexes (KPI), timeline for the set task and utilmately, the expectations to be achieved.


### Project Goals:
1. Track the current status of patient waiting list.
2. Analyze historical monthly trend of waiting list for both inpatient and outpatient categories.
3. Healthcare specialty level and Age profle analysis.

### Data Scope:
Data obtained from 2018 - 2021.

### Metrics Expectations :
1 Average and Median Waitiing List
2. Current Total Wait list.

### Dashboard Views :
1. Summary Page ( Visualizations)
2. Detailed Page or Tabular Analysis.

### Data collection and cleaning phase:

This phase simply covers how data for this task or project will be collected and the sources where data will be generated or pulled out from. This is a very crucial step. It also defines how the data obtained from the stakeholder's databse will be cleaned and tranformed, the tool to be used and to create actionable and refreshable insights. A good execution of this phase lays the right foundation for alll the following steps for the task or project ahead. Power Query in Power BI desktop was used for removing duplicates values, fixing missing values, trimming the values and appending the tables in the folder obtained for this project.


### Transformation and modelling:

In this phase,after the data has been cleaned and transformed, the next step is to model the cleaned data for analysis. This simply involves creating relationships between tables, adding calulated columns and measures. Calculated columns and measures allows one to add new data to a table and to create new metrics from the existing data. DAX ( Data Analysis eXpressions ) was used for calculated columns and to create measures)
Merging both tables into ‘All_data’, I addressed a discrepancy by introducing a new column, ‘case_type’, specifically for the outpatient table, aligning it with the ‘day-case’ and ‘inpatient’ values in the inpatient table.

### Table Connections :

To refine table connections, I manually crafted a specialty table categorizing patient specialties into distinct groups for streamlined dashboard clarity. Furthermore, I established a connection between ‘All_data’ and the ‘Mapping_Specialty’ table based on the ‘Speciality’ column to facilitate a more coherent and insightful analysis within the Power BI dashboard.


### Data Visualization and Blueprint:

This next phase of this Power BI project is to create visualizations that communicate the insights from the data. This involves creating graphs, charts and other visuals that help to tell a story with the data.. It is important to think about the audience for the visuals and how to best communicate the information in an understandable way. After the visuals are created, they can be arranged on a report canvas to create a "blueprint" for the final report. The blueprint gives an overview of the story being told with the data. 


### Dashboard layout and design phase :

The next phase of a Power BI project is to design the dashboard layout. This involves arranging the visuals on the report canvas in a way that's visually appealing and easy to understand. It's important to consider the order and placement of the visuals, as well as the use of color, size, and other design elements. The goal is to create a dashboard that is both informative and visually appealing whilst keeping the audience in mind.

Furthermore, a secondary page containing detailed patient information, equipped with various filters for easy navigation, completes the dashboard, allowing users to delve deeper into specific data points. This blueprint aims to present a holistic view while enabling users to explore nuanced details through an intuitive and informative layout.

### Interactivity and Navigation :

 In this phase of a Power BI project, the goal is to make the dashboard interactive and easy to navigate. This involves adding buttons, slicers, filters, and other controls that allow users to explore the data and interact with the visuals. It's also important to make sure the dashboard is easy to navigate by using clear labels and titles.

### Analysis and Visualization

How does the current year’s total waitlist compare to the previous year?
How many Patient falls under which Case Type?
How does the duration of hospital stays vary across different age groups of patients?
What are the top 5 wait lists by specialty?
What are the monthly trends observed among patients with different case types?




### Testing :

Testing is an important part of any Power BI project, for this project, it was conducted throughout the development process. In this phase, I tested all the visuals, filters, buttons, and other elements to make sure they're working as expected without gliches or errors.

###Sharing and insights :

The goal here is to share the dashboard with stakeholders and other users and generate insights from the data. Power BI has a number of sharing options, including publishing the dashboard to the Power BI service, exporting it to a file, or embedding it on a website. It's also important to generate insights from the data by creating reports, dashboards, and other visualizations that help users understand the data.


## RECOMMENDATIONS :

The increase in the current year’s waitlist to over 700,000 individuals, compared to the previous year’s 640,000, indicates a notable surge in demand for healthcare services. This growth of over 60,000 patients signifies a substantial uptick in the number of individuals seeking inpatient and outpatient care within the given timeframe. Several factors might contribute to this upsurge, such as population growth, changes in healthcare needs, extended referral times, or variations in healthcare policies impacting access to services,

For Case type, insights shows that a large majority, around 72%, fall under the ‘outpatient’ category, indicating that most people visit for treatments that don’t require a hospital stay. On average, this category accounts for nearly 80 patients seeking this type of care. Comparatively, ‘inpatient’ cases, needing hospital stays, represent a smaller share at 11%, while ‘day_case’ holds 17% of the distribution. This data emphasizes the high demand for outpatient services, suggesting a need for efficient management to cater to this significant portion of patients seeking care without hospital admission. Understanding these proportions helps healthcare facilities tailor their services better to meet patient needs effectively.


The duration of hospital stays categorized by age groups: 0–15, 16–64, and 65+ as revealed by the stacked bar chart, The data indicates that a substantial number of patients across various age brackets experience hospital stays lasting 18 months or more. This extended duration is notably prevalent among different age groups, with 66 individuals from the 65+ age group, 136 from the 16–64 age group, and 101 patients from the 0–15 age group. 

Also, a pattern was observed highlighting that the age group spanning 16–64 years represents the majority of admitted patients across different stay durations. This observation suggests a higher rate of hospitalization within the 16–64 age bracket compared to the other age groups. Understanding this pattern aids healthcare providers in tailoring specialized care and resources for this age range, potentially addressing specific health needs or conditions prevalent within this demographic.

The analysis of the top 5 waitlisted specialties reveals a notable trend towards Urology, as it  the specialty emerges at the top of the list with an average waitlist of 47% patients, closely followed by Vascular surgery with 30%  patients. Additionally, Substance abuse, and Pediatric Orthopedic specialties follow suit in the rankings.

The line graphs depicts trends from 2018 to 2021 illustrates relatively stable figures for day-case and inpatient cases, hovering around 57,000–60,000 for day-case and 22,000–23,000 for inpatient services. Contrastingly, there’s a noticeable and substantial upward trend in outpatient cases, rising from 0.5 million to 0.63 million over the same period. The substantial rise in outpatient cases observed over the years could be influenced by several factors: Patient Preferences, Advancements in Medical Technology, Healthcare Policies:, Efficiency and Effectiveness and  Shift in Healthcare Practices,

In conclusion, our observations via the analyzed data unveiled key insights into healthcare trends. The data showcased a significant surge in outpatient cases over the years, indicating a shift towards non-hospital-stay treatments. Urology specialties emerged as focal points, with high waitlists, emphasizing the need for specialized care for children. Furthermore, stable figures were noted for inpatient and day-case services. Factors like technological advancements and patient preferences likely drive the rise in outpatient care. Understanding these trends is vital for healthcare providers to meet evolving patient needs effectively and allocate resources efficiently.
