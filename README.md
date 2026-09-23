<div align="center">

# 💻 1% Laptop Empowerment Initiative — Applicant & Impact Analytics

### Turning Applicant Data into Actionable Insights for Digital Empowerment

<p>
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/Power%20Query-Data%20Cleaning-5E5E5E?style=for-the-badge">
  <img src="https://img.shields.io/badge/DAX-Data%20Modeling-4472C4?style=for-the-badge">
  <img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
</p>

<p>
  <strong>Data Analyst | Operations Analyst</strong>
</p>

<p>
  <em>Using data to understand people, identify needs, and support better digital empowerment decisions.</em>
</p>

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Project Objectives](#-project-objectives)
- [Project Snapshot](#-project-snapshot)
- [Tools & Technologies](#-tools--technologies)
- [Analytical Workflow](#-analytical-workflow)
- [Dataset](#-dataset)
- [Data Cleaning & Transformation](#-data-cleaning--transformation)
- [Key Analytical Areas](#-key-analytical-areas)
- [Power BI Dashboard](#-power-bi-dashboard)
- [Key Performance Indicators](#-key-performance-indicators)
- [Business Questions](#-business-questions)
- [DAX Measures](#-dax-measures)
- [Data Privacy](#-data-privacy)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [Project Impact](#-project-impact)
- [Author](#-author)

---

# 📊 Project Overview

The **1% Laptop Empowerment Initiative** is a data-driven project focused on analyzing applications received from individuals seeking access to laptops and digital resources.

The project transforms raw applicant responses into structured information that can help program administrators understand:

- Who the applicants are
- Where applicants are located
- Their current employment or educational situations
- Their level of experience
- Their access to laptops
- How limited access to technology affects their productivity
- What they intend to achieve with a laptop
- Their career and professional aspirations
- How they intend to create impact within their communities
- How applicants discovered the initiative

The analysis was developed using **Excel, Power Query, Power BI and DAX**, with a focus on turning unstructured application responses into useful program intelligence.

---

# 🎯 Project Objectives

The main objectives of this project are to:

1. Clean and standardize applicant data.
2. Transform unstructured Google Form responses into analysis-ready data.
3. Understand the demographic composition of applicants.
4. Identify applicants with limited or unreliable access to laptops.
5. Analyze the relationship between laptop access and career aspirations.
6. Identify the major professional and educational goals of applicants.
7. Understand the potential social impact of laptop access.
8. Analyze how applicants discovered the initiative.
9. Build an interactive Power BI dashboard.
10. Provide insights that can support future program planning and resource allocation.

---

# 📌 Project Snapshot

| Metric | Description |
|---|---|
| 👥 Applications | 115 |
| 📋 Fields | 24 |
| 📊 Primary Tool | Power BI |
| 🧹 Data Cleaning | Power Query |
| 📈 Data Modeling | Power BI / DAX |
| 📑 Data Source | Applicant Application Form |
| 🎯 Project Type | Social Impact / Digital Empowerment Analytics |

---

# 🛠️ Tools & Technologies

### Microsoft Excel

Used for:

- Initial data inspection
- Data validation
- Basic data preparation
- Reviewing raw application responses

### Power Query

Used for:

- Data cleaning
- Removing unnecessary fields
- Standardizing text
- Handling inconsistencies
- Categorizing free-text responses
- Preparing the dataset for analysis

### Power BI

Used for:

- Data modeling
- Interactive dashboards
- KPI development
- Data visualization
- Applicant segmentation
- Interactive filtering

### DAX

Used for:

- Measures
- KPI calculations
- Percentage calculations
- Applicant segmentation
- Analytical metrics

---

# 🔄 Analytical Workflow

```text
                    RAW APPLICATION DATA
                             │
                             ▼
                    DATA PROFILING
                             │
                             ▼
                    DATA CLEANING
                             │
                             ▼
                  POWER QUERY TRANSFORMATION
                             │
                             ▼
                    DATA STANDARDIZATION
                             │
                             ▼
                     DATA CATEGORIZATION
                             │
                             ▼
                      DATA MODELING
                             │
                             ▼
                     DAX CALCULATIONS
                             │
                             ▼
                    POWER BI DASHBOARD
                             │
                             ▼
                  INSIGHTS & DECISION SUPPORT
Dataset

The original dataset was collected through an application form for the 1% Laptop Empowerment Initiative.

The dataset contains information covering several dimensions of each application.

Applicant Identification
Full Name
Applicant Email
Phone Number
LinkedIn Profile
Demographics
Gender
Age Range
Location
Career Information
Profession
Current Situation
Years of Experience
Application Acquisition
How the applicant heard about the initiative
Laptop Access
Current laptop situation
How access to a laptop could affect the applicant
Future Goals
Intended use of the laptop
12-month goals
Social Impact
Expected impact on others
Ripple effect within the community
Motivation
Why the applicant believes the initiative should invest in them
🧹 Data Cleaning & Transformation

The raw application data contained a mixture of structured fields and long-form text responses.

Power Query was used to transform the data into a cleaner analytical structure.

1. Column Renaming

Long Google Form questions were renamed into concise analytical fields.

Example:

Original:
"What is your current laptop situation?"

Renamed:
Laptop Situation

Other examples include:

Full Name
Applicant Email
Phone
Gender
Age Range
Location
Profession
Current Situation
Experience
Referral Source
Laptop Situation
Laptop Impact
Laptop Goals
12-Month Goals
Social Impact
Ripple Effect
Investment Case
2. Text Cleaning

Text fields were cleaned using:

Trim
Clean
Replace Values
Standardization
Lowercase
Proper Case where appropriate

This helped reduce inconsistencies caused by:

Extra spaces
Different capitalization
Minor spelling variations
Inconsistent responses
📍 Location Standardization

Applicant locations were standardized into meaningful geographic categories.

Examples of inconsistent entries included variations such as:

Lagos
Lagos Nigeria
Surulere Lagos Nigeria
Ajah Lagos Nigeria

These were transformed into standardized geographic fields such as:

City
State
Country

This makes it possible to analyze:

Applicants by city
Applicants by state
Geographic concentration
Potential areas for future outreach
👨‍💼 Profession Categorization

Because applicants entered professions as free-text responses, profession categories were created to support analysis.

Suggested categories include:

Category	Examples
🎓 Student	University students, undergraduates
👨‍🏫 Education	Teachers, tutors, educators
💻 Technology	Developers, IT professionals
📊 Data & Analytics	Data analysts, data professionals
🎨 Creative & Media	Designers, content creators
💼 Business	Entrepreneurs, business owners
🏢 Administration	Administrative professionals
📞 Customer Service	Customer support roles
💰 Finance	Accounting, banking, finance
📣 Sales & Marketing	Marketers, sales professionals
🏥 Healthcare	Health professionals
🔎 Job Seeker	Applicants currently seeking employment
📌 Other	Roles outside the major categories
