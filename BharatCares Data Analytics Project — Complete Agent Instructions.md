# BharatCares Data Analytics / Generative AI Project
## Complete Project-Building, Documentation & Submission Instructions

---

## 1. ROLE OF THE AI AGENT

You are responsible for helping build a complete Data Analytics / Data Science / Generative AI project for the BharatCares internship/masterclass submission.

Do not treat this as only a coding task.

The project must follow this complete philosophy:

**Data → Information → Insight → Decision → Action**

The final project must demonstrate that the data is being converted into meaningful, actionable insights rather than simply producing charts or a complex machine-learning model.

The project should be:

- Practical
- Understandable
- Well documented
- Visually clear
- Reproducible
- Easy for an evaluator to run
- Business/problem oriented
- Based on a legitimate dataset
- Properly structured for GitHub submission

---

# 2. MOST IMPORTANT PROJECT PRINCIPLE

Do NOT optimize the project for:

- Maximum number of charts
- Maximum number of pages
- Maximum amount of code
- Maximum number of filters
- Unnecessary ML models
- Unnecessary complexity

A simple project that produces useful decisions is preferable to a complicated project that produces no meaningful action.

The project should answer:

1. What is happening?
2. What is the trend?
3. Why is it happening?
4. What are the important drivers?
5. What are the risks?
6. What are the opportunities?
7. What should be done?

---

# 3. REQUIRED ANALYTICAL FLOW

Follow this analytical hierarchy:

```text
RAW DATA
    ↓
DATA CLEANING
    ↓
EXPLORATORY DATA ANALYSIS
    ↓
DATA ANALYSIS
    ↓
KPIs
    ↓
TRENDS
    ↓
DRIVERS
    ↓
RISKS & OPPORTUNITIES
    ↓
INSIGHTS
    ↓
DECISION
    ↓
ACTION / RECOMMENDATION
```

If appropriate:

```text
HISTORICAL DATA
       ↓
PREDICTIVE MODEL
       ↓
PREDICTION
       ↓
DECISION
       ↓
ACTION
```

A prediction model is NOT mandatory.

Use machine learning only if it adds meaningful value to the problem.

---

# 4. PROJECT TOPIC SELECTION

Choose a problem that is related to the topics taught during the Data Analytics / Generative AI masterclasses.

Possible domains include:

- E-commerce
- Healthcare
- Finance
- Education
- Environment
- Customer analytics
- Sales analytics
- Marketing
- Social data
- Government/open data
- Transportation
- Agriculture
- Energy
- Any other legitimate analytics problem

The topic must have a clear problem statement.

Do not create a project merely because the dataset looks interesting.

First identify:

```text
Problem
↓
Why it matters
↓
What data can help solve it
↓
What decisions can be made
```

---

# 5. DATASET REQUIREMENT

## CRITICAL RULE

DO NOT use the exact dataset that was provided/used during the BharatCares masterclasses as the learning dataset.

Using the same learning dataset may be considered plagiarism and may make the project ineligible for evaluation.

Use a NEW dataset.

Possible sources:

- Kaggle
- Tableau Public
- Government open-data portals
- Census/open government datasets
- Other legitimate public datasets
- A personally collected dataset, provided it can be accessed by the evaluator

---

# 6. DATASET SOURCE REQUIREMENT

The project MUST document where the dataset came from.

The README must contain a working dataset source link.

Example:

```text
Dataset Source:
https://example.com/dataset
```

If the dataset is hosted privately, provide an accessible link through an appropriate service such as Google Drive or GitHub, with the necessary access permissions.

The evaluator must be able to understand where the dataset originated.

Do NOT invent dataset links.

---

# 7. DATA UNDERSTANDING

Before building the dashboard/model, inspect the dataset.

Determine:

- Number of rows
- Number of columns
- Column names
- Data types
- Missing values
- Duplicate rows
- Outliers
- Unique values
- Categorical variables
- Numerical variables
- Date/time fields
- Target variable, if applicable
- Relationships between variables

Create a clear data dictionary.

Example:

| Column | Type | Description |
|---|---|---|
| customer_id | Integer/String | Unique customer |
| revenue | Float | Revenue generated |
| order_date | Date | Date of order |
| category | String | Product category |

---

# 8. DATA CLEANING

Clean the dataset before analysis.

Check for:

- Missing values
- Duplicate records
- Incorrect data types
- Invalid dates
- Inconsistent categories
- Currency symbols
- Formatting problems
- Outliers
- Impossible values
- Incorrect labels
- Empty columns
- Unnecessary columns

Document what was changed.

Do not silently modify important data.

The project should explain:

```text
Problem found
↓
Cleaning method
↓
Reason
↓
Result
```

---

# 9. EXPLORATORY DATA ANALYSIS

Perform EDA to understand what the data is saying.

Analyze appropriate dimensions such as:

- Time
- Geography
- Category
- Customer segment
- Product
- Revenue
- Quantity
- Profit
- Demographics
- Other domain-specific dimensions

Use appropriate visualizations.

Possible charts:

- Bar chart
- Line chart
- Histogram
- Scatter plot
- Box plot
- Heatmap
- Area chart
- KPI cards
- Maps, if geographic data exists

Do NOT create charts just to increase the number of charts.

Every important visualization should answer a question.

---

# 10. KPI IDENTIFICATION

Identify the most meaningful KPIs for the selected project.

KPIs are NOT fixed.

Choose KPIs based on the project.

For an e-commerce project, possible examples are:

- Revenue
- Orders
- Customers
- Average Order Value
- Profit
- Growth %

For education:

- Average Marks
- Attendance %
- Pass %
- Subject Performance
- Average CGPA

For healthcare:

- Patient Count
- Recovery Rate
- Average Treatment Time
- Readmission Rate

For environmental analysis:

- Average AQI
- PM2.5
- PM10
- Severe Pollution Days

The agent must NOT blindly copy e-commerce KPIs into another domain.

Choose KPIs that best represent performance.

Prefer a small number of high-value KPIs rather than overwhelming the user.

---

# 11. KPI SELECTION PRINCIPLE

Do not automatically show every available metric.

Ask:

> "If the user could only see a few numbers, which numbers would help them understand the situation fastest?"

The dashboard should prioritize clarity.

Possible structure:

```text
KPI 1
KPI 2
KPI 3
KPI 4
```

Then detailed analysis below.

---

# 12. TREND ANALYSIS

For important KPIs, identify trends.

Examples:

- Revenue increasing/decreasing
- Customer growth
- Sales fluctuations
- Seasonal changes
- Monthly performance
- Year-over-year changes
- Category trends

The analysis must explain what the trend means.

Do not merely display:

> Sales decreased by 20%.

Explain:

> Sales decreased by 20%, primarily due to reduced performance in Category X / Region Y.

Only make such claims if supported by the data.

---

# 13. DRIVER ANALYSIS

For important changes, identify possible drivers.

Ask:

> WHY is this happening?

Example:

```text
Sales decreased
↓
Region X declined
↓
Category Y declined
↓
High-value customers decreased
```

Drivers can include:

- Product category
- Region
- Customer segment
- Price
- Seasonality
- Marketing
- Demand
- Operational factors
- Other variables present in the dataset

Do not invent drivers.

Only use evidence available in the dataset.

---

# 14. RISK ANALYSIS

Identify meaningful risks.

Ask:

> What could negatively affect the outcome/business/project?

Examples:

- Customer churn
- Falling sales
- Low-performing products
- High-risk customer groups
- Increasing costs
- Declining engagement
- Pollution risk
- Student performance risk

Risk statements must be data-supported.

---

# 15. OPPORTUNITY ANALYSIS

Identify where improvement or growth may be possible.

Examples:

- High-performing product category
- Growing customer segment
- Strong geographic market
- Increasing demand
- Underutilized resource
- High-performing channel

Again, do not invent opportunities.

They must be supported by the analysis.

---

# 16. ACTION / RECOMMENDATION

The project must ultimately answer:

> "What should the decision-maker do?"

Recommendations should be specific.

Weak:

```text
Improve sales.
```

Better:

```text
Focus retention efforts on high-value customers in the declining region.
```

Even better, if supported by the data:

```text
Launch a targeted retention campaign for high-value customers in Region X,
where churn risk has increased and revenue has declined.
```

The action should logically follow from:

```text
Fact → Insight → Risk/Opportunity → Action
```

---

# 17. DASHBOARD STRUCTURE

The project may use one page or multiple pages.

There is NO mandatory number of pages.

Use the minimum number of pages required to communicate the analysis clearly.

A possible structure is:

## Page 1 — Executive Overview

Show:

- Main KPIs
- Overall trends
- Important findings
- High-level summary
- Key risks
- Key opportunities

## Page 2 — Sales/Product/Domain Analysis

Show domain-specific analysis.

For e-commerce:

- Product performance
- Category performance
- Sales trends
- Regional analysis

## Page 3 — Customer/Risk Analysis

Show:

- Customer segments
- Customer behavior
- Risk indicators
- Churn
- Opportunities
- Recommended actions

This structure is an example, NOT a mandatory requirement.

---

# 18. USER EXPERIENCE PRINCIPLE

The dashboard should be designed for someone who does NOT understand the backend.

The evaluator/user should quickly understand:

- What is happening?
- Why?
- What is important?
- What is risky?
- What is the opportunity?
- What should be done?

Do not force the user to inspect dozens of charts to find the answer.

---

# 19. AI USAGE

AI tools such as IBM Bob or other suitable AI tools may be used.

AI can assist with:

- Data cleaning
- EDA
- Code generation
- Visualization
- Machine learning
- Documentation
- README generation
- Project report generation

However:

## DO NOT blindly trust AI output.

Verify:

- Calculations
- Charts
- Model metrics
- Dataset columns
- Data source
- Code
- Recommendations

Do not fabricate results.

---

# 20. IBM BOB / AI AGENT PROMPTING

When using an AI coding agent, provide a detailed prompt.

Do NOT simply say:

```text
Build me a project.
```

Instead specify:

- Dataset
- Problem statement
- Domain
- KPIs
- Analysis
- Dashboard requirements
- Model requirements
- Documentation
- Required files
- Single-code-file requirement
- Dataset source
- Output screenshots
- README
- Project report

---

# 21. SINGLE CODE FILE REQUIREMENT

For this submission, prefer creating a single main code file wherever practical.

Example:

```text
project.py
```

or:

```text
project.ipynb
```

The code should contain the necessary project functionality.

Avoid unnecessarily creating many separate code files because the submission form expects a single code file.

If a frontend/backend/ML application is created, combine the required functionality into one code submission file where technically practical.

NOTE:

This is a submission simplification requirement. It is NOT necessarily ideal production architecture.

---

# 22. REQUIRED FINAL FILES

The final project MUST produce these four main deliverables:

## FILE 1 — CODE

Accepted:

```text
.py
```

or:

```text
.ipynb
```

The code must contain the actual project implementation.

---

## FILE 2 — REQUIREMENTS

Filename:

```text
requirements.txt
```

This file must contain all Python libraries/dependencies required to run the project.

Example:

```text
pandas
numpy
matplotlib
scikit-learn
streamlit
```

Prefer including appropriate versions when possible.

IMPORTANT:

Every library imported by the project should be represented in requirements.txt.

Do not leave required dependencies out.

---

## FILE 3 — README

Filename:

```text
README.md
```

The README must include:

1. Project title
2. Project overview
3. Problem statement
4. Objective
5. Dataset description
6. Dataset source link
7. Dataset fields/data dictionary
8. Technologies used
9. Data cleaning methodology
10. EDA methodology
11. KPIs
12. Key insights
13. Model details, if applicable
14. Model evaluation, if applicable
15. Dashboard details
16. How to install
17. How to run
18. Expected output
19. Risks
20. Opportunities
21. Recommendations/actions
22. Limitations
23. Future scope
24. Project structure

---

# 23. README — REQUIRED DATASET SECTION

Include:

```text
## Dataset

Dataset Name:
[Name]

Source:
[Working URL]

Rows:
[Number]

Columns:
[Number]

Description:
[Description]
```

If the dataset is from Kaggle or another public source, include the exact source URL.

---

# 24. README — HOW TO RUN

Include clear commands.

Example:

```bash
pip install -r requirements.txt
```

If using Streamlit:

```bash
streamlit run project.py
```

If using normal Python:

```bash
python project.py
```

Use the command that actually matches the project.

Do NOT provide commands that do not work.

---

# 25. PROJECT REPORT

Create a professional project report in DOCX or PDF format.

Recommended structure:

## Cover Page

- Project Title
- Student Name
- Institution
- Program/Course
- Internship/Masterclass
- Date

## 1. Introduction

Explain the project.

## 2. Problem Statement

Clearly explain the problem.

## 3. Objectives

List objectives.

## 4. Dataset

Explain:

- Source
- Size
- Variables
- Data types

## 5. Data Cleaning

Explain:

- Missing values
- Duplicates
- Outliers
- Transformations

## 6. Exploratory Data Analysis

Explain major findings.

Include relevant charts.

## 7. KPIs

Explain selected KPIs and why they matter.

## 8. Methodology

Explain the workflow.

## 9. Machine Learning Model

Include only if used.

Explain:

- Algorithm
- Training
- Testing
- Metrics
- Results

## 10. Dashboard / UI

Include screenshots of the actual UI/output.

## 11. Key Insights

List major findings.

## 12. Risks

List data-supported risks.

## 13. Opportunities

List data-supported opportunities.

## 14. Recommended Actions

Explain what should be done.

## 15. Conclusion

Summarize the result.

## 16. Future Scope

Explain possible improvements.

---

# 26. UI SCREENSHOTS

The project report should contain screenshots of the project's UI/output.

Screenshots should demonstrate:

- Main dashboard
- Important visualizations
- KPIs
- Prediction output, if applicable
- Important insights

Screenshots must be real outputs from the project whenever possible.

Do not fabricate screenshots.

---

# 27. GITHUB REQUIREMENT

Create a GitHub repository for the project.

Recommended structure:

```text
PROJECT-NAME/
│
├── project.py
├── requirements.txt
├── README.md
└── Project_Report.pdf
```

If the report is DOCX:

```text
PROJECT-NAME/
│
├── project.py
├── requirements.txt
├── README.md
└── Project_Report.docx
```

---

# 28. GITHUB REPOSITORY CHECK

Before submission verify:

- Repository is accessible
- Code is uploaded
- requirements.txt is uploaded
- README.md is uploaded
- Report is uploaded
- Dataset link is present in README
- Instructions work
- No unnecessary ZIP file
- No missing required files

---

# 29. SUBMISSION FORM

The BharatCares team will provide the official submission form.

The form is expected to require:

1. Code file
2. Requirements file
3. Project report
4. README file
5. GitHub repository link
6. Other basic/meta information requested by the form

Fill the form exactly according to the instructions provided by the BharatCares team.

Do not assume field names if the official form provides different names.

---

# 30. IMPORTANT FILE-NAMING RULE

The BharatCares team said that the submission form/resource document will specify the required file naming format.

Therefore:

1. Generate the required files.
2. When the official form/resource document is available, check the exact naming requirements.
3. Rename files to match the official instructions.
4. Do not invent a naming convention if an official one is provided.

---

# 31. IMPORTANT DEADLINE RULE

The exact final submission deadline was NOT confirmed during the class.

The trainers said the exact deadline would be communicated through the WhatsApp group.

Therefore:

DO NOT assume that a specific date is the deadline.

Before final submission:

```text
Check official WhatsApp announcement
        ↓
Confirm deadline
        ↓
Confirm submission form
        ↓
Confirm required file names
        ↓
Submit
```

The trainer indicated that students would have approximately at least two weeks, but this should NOT be treated as the official deadline.

---

# 32. DO NOT USE THE MASTERCLASS DATASET

This is one of the most important rules.

The learning dataset used during the masterclasses must NOT be reused as the final project dataset.

The final project should use a new dataset.

Before building the project, verify:

```text
Is this the exact masterclass dataset?
        ↓
YES → DO NOT USE
NO → Can be considered
```

---

# 33. PROJECT QUALITY STANDARD

The project should NOT be evaluated by:

- Number of charts
- Number of pages
- Number of lines of code
- Complexity of ML algorithm

Instead, prioritize:

### Problem clarity

Can someone understand what problem is being solved?

### Data relevance

Does the dataset actually help solve the problem?

### Analytical quality

Does the analysis produce meaningful findings?

### KPI relevance

Do the KPIs represent the problem?

### Visualization quality

Are charts understandable?

### Insight quality

Does the project explain WHY something is happening?

### Actionability

Does the project tell the user what to do?

### Documentation

Can another person understand and run the project?

### Reproducibility

Can the evaluator install dependencies and run the code?

---

# 34. MODEL REQUIREMENT

Machine learning is OPTIONAL.

Use ML when it adds value.

Examples:

```text
Sales Forecasting
Customer Churn Prediction
House Price Prediction
Loan Approval Prediction
Disease Risk Prediction
AQI Prediction
Student Performance Prediction
```

If ML is used, include:

- Target variable
- Features
- Train/test split
- Model
- Evaluation metrics
- Results
- Interpretation

Do not add an ML model simply to make the project appear advanced.

---

# 35. IF NO ML MODEL IS USED

That is acceptable if the project can achieve its objective through analytics.

For example:

```text
Dataset
↓
Cleaning
↓
EDA
↓
KPI Analysis
↓
Trend Analysis
↓
Risk Analysis
↓
Opportunity Analysis
↓
Recommendations
```

This can still be a complete Data Analytics project.

---

# 36. RECOMMENDATION LOGIC

Every recommendation should have evidence.

Use:

```text
FACT
↓
INSIGHT
↓
REASON
↓
ACTION
```

Example:

```text
FACT:
Region X revenue decreased 25%.

INSIGHT:
Region X is the primary contributor to overall revenue decline.

RISK:
Continued decline may reduce total revenue.

ACTION:
Investigate Region X customer/product performance and launch
targeted retention or demand-generation activities.
```

Do not make unsupported recommendations.

---

# 37. DASHBOARD DESIGN PRINCIPLES

The dashboard should be:

- Clean
- Professional
- Responsive if applicable
- Easy to understand
- Consistent
- Not overloaded
- Clearly labeled

Use meaningful titles.

Bad:

```text
Chart 1
Chart 2
Chart 3
```

Better:

```text
Monthly Revenue Trend
Revenue by Region
Top Performing Categories
Customer Churn Risk
```

---

# 38. AI-GENERATED CODE VERIFICATION

After generating the project:

1. Install requirements.
2. Run the project.
3. Fix errors.
4. Verify every major chart.
5. Verify KPI calculations.
6. Verify model metrics.
7. Verify dataset loading.
8. Verify UI.
9. Take screenshots.
10. Update README.
11. Update report.
12. Perform final submission check.

Do NOT submit code that has not been tested.

---

# 39. REQUIREMENTS.TXT VERIFICATION

Before finalizing:

```text
For every import:
    ↓
Check corresponding package
    ↓
Check requirements.txt
```

Make sure there are no missing dependencies.

The evaluator may install requirements first and then run the code.

---

# 40. README VERIFICATION

Check that README contains:

```text
☐ Project title
☐ Problem statement
☐ Objective
☐ Dataset
☐ Dataset source link
☐ Technologies
☐ KPIs
☐ Analysis
☐ Model information
☐ Insights
☐ Risks
☐ Opportunities
☐ Recommendations
☐ Installation
☐ Run instructions
☐ Project structure
☐ Limitations
☐ Future scope
```

---

# 41. FINAL PROJECT DIRECTORY

Before submission, the project directory should look approximately like:

```text
PROJECT/
│
├── project.py
├── requirements.txt
├── README.md
├── Project_Report.pdf
│
└── [optional local development files]
```

Only the required files should be uploaded to the final GitHub repository unless additional files are genuinely required.

---

# 42. FINAL PRE-SUBMISSION CHECKLIST

Run this checklist before declaring the project complete.

## Dataset

- [ ] New dataset selected
- [ ] Not the masterclass learning dataset
- [ ] Dataset source documented
- [ ] Dataset link works
- [ ] Dataset understood

## Analysis

- [ ] Data cleaned
- [ ] EDA performed
- [ ] KPIs selected
- [ ] Trends identified
- [ ] Drivers analyzed
- [ ] Risks identified
- [ ] Opportunities identified
- [ ] Actions/recommendations created

## ML

- [ ] ML used only if useful
- [ ] Model evaluated if used
- [ ] Results verified
- [ ] No fabricated metrics

## Dashboard/UI

- [ ] KPIs visible
- [ ] Important trends visible
- [ ] Charts have meaningful titles
- [ ] UI is understandable
- [ ] Output works
- [ ] Screenshots captured

## Code

- [ ] Code runs
- [ ] No obvious errors
- [ ] Main code is in accepted format
- [ ] Unnecessary multiple code files avoided
- [ ] Dependencies identified

## Files

- [ ] Code file
- [ ] requirements.txt
- [ ] README.md
- [ ] Project Report

## GitHub

- [ ] Repository created
- [ ] All required files uploaded
- [ ] Repository link works
- [ ] README visible
- [ ] Dataset link present

## Submission

- [ ] Official form obtained
- [ ] Exact file naming checked
- [ ] Exact deadline checked
- [ ] Code uploaded
- [ ] requirements.txt uploaded
- [ ] README uploaded
- [ ] Report uploaded
- [ ] GitHub link submitted
- [ ] All required metadata completed
- [ ] Final submission completed

---

# 43. FINAL SUCCESS CRITERIA

The project is considered ready only when all of the following are true:

```text
NEW DATASET
     ↓
CLEAR PROBLEM
     ↓
CLEAN DATA
     ↓
ANALYSIS
     ↓
RELEVANT KPIs
     ↓
CLEAR VISUALIZATIONS
     ↓
DATA-SUPPORTED INSIGHTS
     ↓
RISKS / OPPORTUNITIES
     ↓
ACTIONABLE RECOMMENDATIONS
     ↓
WORKING PROJECT
     ↓
DOCUMENTATION
     ↓
4 REQUIRED FILES
     ↓
GITHUB REPOSITORY
     ↓
OFFICIAL SUBMISSION FORM
```

---

# 44. AGENT'S FINAL INSTRUCTION

Do not stop after generating code.

The complete task is:

1. Select a new and relevant dataset.
2. Define the problem.
3. Analyze and clean the data.
4. Identify meaningful KPIs.
5. Perform EDA.
6. Build useful visualizations/dashboard.
7. Identify trends.
8. Identify drivers.
9. Identify risks.
10. Identify opportunities.
11. Generate actionable recommendations.
12. Add an ML model only if it provides meaningful value.
13. Create a working project.
14. Test the project.
15. Generate `requirements.txt`.
16. Generate `README.md`.
17. Generate the project report.
18. Include UI/output screenshots in the report.
19. Verify all four files.
20. Create a GitHub repository.
21. Upload the four required files.
22. Verify the repository.
23. Prepare the submission-form information.
24. Wait for/verify the official BharatCares submission form and exact deadline.
25. Submit the project according to the official form instructions.

The final project should demonstrate:

**DATA → INSIGHT → DECISION → ACTION**

rather than simply:

**DATA → CHARTS.**