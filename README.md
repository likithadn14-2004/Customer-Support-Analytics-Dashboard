#  Customer Support Analytics Dashboard

An interactive **Customer Support Analytics Dashboard** developed using **Microsoft Power BI** to analyze customer support operations, ticket trends, customer satisfaction, escalation patterns, issue distribution, and agent performance.

This project was developed as part of the **Data Analytics with Python internship** at **Dyashin Technosoft Pvt Ltd, Bengaluru**, through its training division DSEdify.

---

##  Project Overview

Customer support departments handle a large number of customer queries through different communication channels such as calls, chats, emails, and social media. Traditional reporting methods can make it difficult to monitor ticket handling, customer satisfaction, escalation patterns, and agent efficiency.

This project addresses this problem by developing an interactive Power BI dashboard that transforms customer support data into meaningful visual insights for operational monitoring and decision-making.

---

##  Objectives

* Analyze overall customer support performance
* Monitor total, open, and closed tickets
* Analyze ticket trends over time
* Monitor customer satisfaction
* Analyze ticket escalation patterns
* Identify common customer issue types
* Compare ticket distribution across priorities
* Analyze ticket resolution time
* Evaluate support agent performance
* Analyze support activity across communication channels and regions
* Provide interactive and data-driven insights for decision-making

---

##  Technologies & Tools

| Technology      | Purpose                                         |
| --------------- | ----------------------------------------------- |
| **Power BI**    | Dashboard development and business intelligence |
| **Power Query** | Data cleaning and transformation                |
| **DAX**         | KPI and analytical calculations                 |
| **Python**      | Data preprocessing and analysis                 |
| **Pandas**      | Data manipulation                               |
| **NumPy**       | Numerical operations                            |
| **SQL**         | Data querying and database operations           |
| **Tableau**     | Data visualization and business intelligence    |
| **CSV**         | Customer support dataset                        |

The internship provided practical exposure to Python, SQL, Power BI, Tableau, data preprocessing, visualization, and business intelligence workflows.

---

#  Project Structure

```text
Customer-Support-Analytics-Dashboard/
│
├── Customer_Support_Analytics.pbix
│
├── screenshots/
│   ├── dashboard1_overview.png
│   ├── dashboard2_issue_analysis.png
│   └── dashboard3_agent_performance.png
│
├── dataset/
│   └── customer_support_dataset.csv
│
└── README.md
```

> **Note:** The dataset should only be uploaded if you have permission to redistribute it.

---

#  Dashboard 1: Customer Support Overview

The first dashboard provides a high-level overview of customer support operations, ticket management, and service performance.

### Key Performance Indicators

* Total Tickets
* Open Tickets
* Closed Tickets
* Average Satisfaction Score
* Escalation Rate

### Visualizations

* Tickets by Priority
* Tickets by Month
* Tickets by Communication Channel
* Average Resolution Time by Priority
* Ticket Status Distribution
* Region-based filtering

### Dashboard Preview

![Customer Support Overview](screenshots/dashboard1_overview.png)

The analysis showed that medium-priority tickets represented a comparatively larger portion of the workload. Calls and social media generated a larger number of support requests compared with other communication channels.

---

#  Dashboard 2: Issue Type Analysis

The second dashboard focuses on customer issue distribution, escalation patterns, ticket priorities, and regional support activity.

### Visualizations

* Tickets by Priority
* Tickets by Issue Type
* Escalation Analysis by Issue Type
* Average Resolution Time by Priority
* Tickets by Region

### Interactive Filters

* Priority
* Status

### Dashboard Preview

![Issue Type Analysis](screenshots/dashboard2_issue_analysis.png)

This dashboard helps identify frequently reported customer issues, issue categories with higher escalation rates, regional workload distribution, and ticket resolution patterns.

---

#  Dashboard 3: Agent Performance Analysis

The third dashboard evaluates support agent performance and operational efficiency.

### Key Performance Indicators

* Average Resolution Time
* Average Response Time
* Feedback Rate
* Resolution Rate

### Visualizations

* Tickets by Agents
* Average Satisfaction by Agents
* Average Resolution Time by Agents
* Average Satisfaction by Channel

### Interactive Filters

* Ticket Status
* Priority
* Region

### Dashboard Preview

![Agent Performance Analysis](screenshots/dashboard3_agent_performance.png)

The dashboard helps compare agent workload, customer satisfaction, resolution efficiency, and service quality. It can also help identify high-performing agents and operational bottlenecks.

---

#  Data Analytics Workflow

The project followed a structured data analytics workflow:

```text
Customer Support Dataset
          ↓
    Data Collection
          ↓
 Data Cleaning & Preprocessing
          ↓
    Data Transformation
          ↓
      Data Analysis
          ↓
      DAX & KPIs
          ↓
   Power BI Visualization
          ↓
 Interactive Dashboards
          ↓
   Business Insights
```

The dataset contained information such as ticket ID, customer ID, issue type, priority, communication channel, ticket status, response time, resolution time, escalation information, customer satisfaction, and agent information.

---

#  Data Cleaning & Preprocessing

Data preprocessing was performed before dashboard development.

The process included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Resolving text formatting issues
* Handling missing Region and Customer ID values
* Preserving valid null values where appropriate
* Creating date-related fields for trend analysis
* Transforming the dataset into an analysis-ready format

Power Query was used for data transformation and preprocessing before visualization in Power BI.

---

#  Power BI Features Used

The project used several Power BI capabilities:

* Power Query
* Data transformation
* Data modeling
* DAX measures
* KPI cards
* Bar charts
* Line charts
* Donut charts
* Tables
* Slicers
* Filters
* Interactive dashboard navigation
* Drill-down analysis

These features were used to convert customer support data into interactive analytical reports.

---

#  Key Insights

The dashboard generated several insights from the customer support dataset:

* Medium-priority tickets formed a comparatively larger portion of the support workload.
* Calls and social media generated a higher number of support requests compared with other channels.
* Medium-priority tickets showed slightly higher average resolution times.
* Certain issue categories showed higher escalation rates.
* Customer satisfaction varied across support agents.
* Agents showed differences in ticket handling and resolution efficiency.
* Email and social media showed comparatively higher customer satisfaction among the analyzed communication channels.
* Regional filtering helped identify differences in support workload.

---

# Testing

The dashboards were tested using different filtering and interaction scenarios.

Testing included:

* Ticket count validation
* KPI calculation verification
* Slicer interaction testing
* Dashboard consistency checks
* Filter behavior validation
* Visualization output verification

The dashboards successfully responded to filtering operations and generated analytical outputs.

---

#  Skills Demonstrated

This project demonstrates practical skills in:

### Data Analytics

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Transformation
* Business Intelligence

### Power BI

* Power Query
* DAX
* Data Modeling
* KPI Development
* Interactive Dashboards
* Data Visualization

### Programming & Databases

* Python
* Pandas
* NumPy
* SQL

### Analytical Skills

* Trend Analysis
* Customer Support Analysis
* Performance Analysis
* Insight Generation
* Data-driven Decision Making

---

# 🚀 How to Run the Project

### Requirements

Install:

* Microsoft Power BI Desktop

### Steps

1. Clone or download this repository.

2. Open:

```text
Customer_Support_Analytics.pbix
```

3. If Power BI asks for the dataset location, update the data source path.

4. Refresh the dataset.

5. Navigate through the dashboard pages.

6. Use the available slicers and filters to interact with the dashboard.

---

#  Dashboard Screenshots

## Customer Support Overview

![Dashboard 1](screenshots/dashboard1_overview.png)

## Issue Type Analysis

![Dashboard 2](screenshots/dashboard2_issue_analysis.png)

## Agent Performance Analysis

![Dashboard 3](screenshots/dashboard3_agent_performance.png)

#  Author

**Likitha D**
