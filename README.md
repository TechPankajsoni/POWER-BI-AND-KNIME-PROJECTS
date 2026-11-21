# 📊 POWER BI AND KNIME PROJECTS

Welcome to my **Power BI and KNIME Projects Repository**! 🚀

This repository contains my practical projects and lab assessments focused on **Data Analytics, Data Cleaning, Data Transformation, Data Visualization, Business Intelligence, Machine Learning, and Dashboard Development**.

These projects demonstrate how raw datasets can be cleaned, processed, analyzed, visualized, and transformed into meaningful insights using **Microsoft Power BI and KNIME Analytics Platform**.

---

## 👨‍💻 About Me

**Name:** Pankaj Soni  
**Field:** MCA (Artificial Intelligence & Machine Learning)  
**Interests:** Data Analytics, Business Intelligence, Python, Machine Learning, and Data Visualization

I am passionate about exploring data, building interactive dashboards, developing machine learning models, and solving real-world problems using data-driven approaches.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Data Visualization & Interactive Dashboards |
| Power Query | Data Cleaning & Transformation |
| DAX | Calculated Columns & Measures |
| KNIME Analytics Platform | Data Processing, Workflows & Machine Learning |
| Decision Tree | Classification & Predictive Modeling |
| Microsoft Excel | Data Preparation & Reporting |
| CSV | Dataset Management |
| Python | Data Analytics & Machine Learning |
| Git & GitHub | Version Control & Project Hosting |

---

## 📁 Repository Contents

### 1. Lab Assessment 1 – Data Cleaning & Preparation

**Objective:** Clean, transform, and merge datasets using Power BI and KNIME to prepare structured data for analysis.

**Tasks Performed:**

- Imported CSV and Excel datasets.
- Identified and handled missing values.
- Removed duplicate records.
- Corrected inconsistent text and letter cases.
- Removed unwanted trailing spaces.
- Filtered, sorted, and grouped data.
- Merged Orders and Customers datasets.
- Applied data transformation techniques.
- Exported the final cleaned dataset.

**Deliverables:**

- Power BI (`.pbix`) project file.
- KNIME workflow (`.knwf`) file.
- Cleaned sales dataset (`.csv`).
- Lab Assessment 1 report (`.pdf`).

**Key Learning:** Gained practical experience in data cleaning, preprocessing, transformation, and dataset integration.

---

### 2. Lab Assessment 2 – Netflix Data Analysis & Dashboard

**Objective:** Analyze the Netflix Movies and TV Shows dataset and develop an interactive Power BI dashboard to identify patterns and trends.

**Tasks Performed:**

- Imported the Netflix dataset into Power BI.
- Cleaned and transformed data using Power Query.
- Performed Exploratory Data Analysis (EDA).
- Created a data model with relationships.
- Developed calculated columns and DAX measures.
- Designed interactive KPI cards.
- Created charts and visualizations.
- Added slicers, maps, and drill-through functionality.
- Developed an interactive dashboard to generate meaningful insights.

**Deliverables:**

- Power BI dashboard (`.pbix`).
- DAX measures and calculated columns.
- Netflix dataset analysis.
- Power BI assignment report (`.pdf`).

**Key Learning:** Developed skills in Power BI dashboard design, DAX calculations, data modeling, and interactive business intelligence reporting.

---

### 3. Lab Assessment 3 – Titanic Survival Prediction Using KNIME

**Objective:** Perform data preprocessing, exploratory data analysis, visualization, and predictive modeling using the Titanic dataset in KNIME Analytics Platform. Develop a Decision Tree classification model to predict passenger survival and evaluate its performance.

#### Task 1: Data Preparation & Cleaning

- Imported the Titanic dataset (`titanic.csv`) using CSV Reader.
- Worked with a dataset containing **891 rows and 12 columns**.
- Used Statistics to examine dataset attributes.
- Identified missing values:
  - Age: 177 missing values.
  - Cabin: 687 missing values.
  - Embarked: 2 missing values.
- Used Column Filter to remove unnecessary columns such as Name, Ticket, and Cabin.
- Applied Missing Value node to handle missing data.
- Used Rule Engine to create a new column named `SurvivedLabel`.
- Converted survival outcomes into categorical values:
  - `Survived = 1` → Yes.
  - `Survived = 0` → No.
- Applied Row Filter to analyze first-class passengers (`Pclass = 1`).
- Used GroupBy to summarize survival rates based on passenger gender.

#### Task 2: Exploratory Data Analysis & Visualization

- Calculated descriptive statistics using the Statistics node.
- Used Color Palette Designer and Color Designer (Apply) to distinguish survival outcomes.
- Created a Bar Chart to compare survival rates by gender.
- Developed a Histogram to analyze passenger age distribution.
- Created a Box Plot to examine fare distribution by gender and identify outliers.
- Designed a Scatter Plot to visualize the relationship between Age and Fare.
- Used Linear Correlation to analyze relationships between numerical attributes.

**Visualizations Created:**

1. Bar Chart – Survival Rate by Gender.
2. Histogram – Passenger Age Distribution.
3. Box Plot – Fare Distribution by Gender.
4. Scatter Plot – Age vs Fare.
5. Correlation Analysis – Relationships Between Numerical Features.

#### Task 3: Decision Tree Classification & Model Evaluation

- Selected relevant features using Column Filter.
- Used Table Partitioner to divide the dataset into training and testing sets.
- Applied a **70% training and 30% testing** data split.
- Built a Decision Tree classification model.
- Selected `SurvivedLabel` as the target variable.
- Used the **Gini Index** as the splitting criterion.
- Applied Decision Tree Predictor to predict passenger survival.
- Evaluated model performance using the Scorer node.
- Generated a confusion matrix to compare actual and predicted results.
- Analyzed Decision Tree classification rules.

**Model Evaluation Results:**

| Metric | Result |
|---|---|
| Algorithm | Decision Tree Classification |
| Target Variable | SurvivedLabel |
| Training Data | 70% |
| Testing Data | 30% |
| Splitting Criterion | Gini Index |
| Correct Predictions | 211 |
| Total Test Records | 268 |
| Model Accuracy | 78.73% |

**Confusion Matrix:**

| Actual / Predicted | No | Yes |
|---|---:|---:|
| No | 143 | 22 |
| Yes | 35 | 68 |

**Decision Tree Rules:**

- IF Sex = female, THEN predict survival as Yes.
- IF Sex = male AND Age greater than 13, THEN predict survival as No.

These rules summarize the visible branches of the trained Decision Tree.

#### Task 4: Workflow Automation & Export

- Organized the KNIME workflow into Prepare, Explore, Model, and Report stages.
- Used Excel Writer to configure the export of prepared data, survival summaries, and model evaluation results.
- Used CSV Writer to configure the export of predicted survival outcomes.
- Connected preprocessing, visualization, prediction, and reporting nodes.
- Documented the workflow with screenshots and model results.

**Key Insights:**

- Female passengers had a higher survival rate than male passengers.
- Passenger gender was an important factor in predicting survival.
- Passenger class and fare showed relationships with survival outcomes.
- Decision Tree classification provided an interpretable approach to survival prediction.
- The model achieved approximately **78.73% accuracy** on the test data.

**Deliverables:**

- KNIME workflow screenshots.
- Titanic dataset (`titanic.csv`).
- Decision Tree visualization.
- Confusion matrix and model evaluation.
- Lab Assessment 3 final report (`2601940058_KNIME_LA3_Final.pdf`).

**Technologies Used:** KNIME Analytics Platform, Decision Tree Classification, Data Preprocessing, Exploratory Data Analysis, Data Visualization, Microsoft Excel, CSV.

**Key Learning:** Gained practical experience in machine learning workflows, classification, feature selection, model training, testing, and performance evaluation using KNIME.

---

## 📂 Files Available

This repository includes:

- `2601940058_LA1` – Lab Assessment 1 project files.
- `knime_assignment` – KNIME assignment and workflow files.
- `2601940058_LA1.pbix` – Power BI Lab 1 project.
- `2601940058_LA1.pdf` – Lab Assessment 1 documentation.
- `knime_student_performance.csv` – Student performance dataset.
- `pankaj_netflixDAX.pbix` – Netflix DAX and Power BI project.
- `2601940058_KNIME_LA3_Final.pdf` – Lab Assessment 3: Titanic Survival Prediction report.
- `README.md` – Project documentation.

---

## 🎯 Key Learning Outcomes

Through these projects, I gained practical experience in:

- Data Cleaning and Data Preprocessing.
- Exploratory Data Analysis (EDA).
- Power Query and Data Transformation.
- DAX Calculations and Measures.
- Data Modeling and Relationships.
- Interactive Dashboard Development.
- KNIME Workflow Design and Automation.
- Data Integration and Merging.
- Business Intelligence and Data Interpretation.
- Decision Tree Classification.
- Machine Learning Model Development.
- Training and Testing Dataset Partitioning.
- Feature Selection and Predictive Modeling.
- Confusion Matrix and Model Accuracy Evaluation.
- Data Visualization and Statistical Analysis.
- Exporting Analytical Results and Reports.

---

## 🚀 How to Explore the Projects



**1. Explore Power BI projects:**

- Open `.pbix` files using Power BI Desktop.
- Explore interactive dashboards, charts, and DAX calculations.

**2. Explore KNIME projects:**

- Open KNIME workflows using KNIME Analytics Platform.
- Review data preprocessing, visualization, and machine learning nodes.
- Explore the Decision Tree classification workflow.

**3. Review project documentation:**

- Open the available PDF reports.
- Explore datasets and project screenshots.
- Review analytical findings and learning outcomes.

---

## 📌 Future Improvements

- Add more real-world data analytics projects.
- Develop advanced Power BI dashboards.
- Explore advanced DAX functions.
- Build automated KNIME data processing workflows.
- Integrate Python with Power BI and KNIME.
- Explore advanced machine learning algorithms.
- Implement Random Forest and Logistic Regression models.
- Compare machine learning model performance.
- Develop end-to-end data analytics projects.
- Create interactive dashboards using real-world datasets.

---

## 🤝 Connect With Me

**GitHub:** [TechPankajsoni](https://github.com/TechPankajsoni)

**LinkedIn:** [Pankaj Soni](https://www.linkedin.com/in/pankaj-soni-6a6606232/)

---

## ⭐ Support

If you find this repository useful, feel free to explore the projects and connect with me.

**Learning | Building | Analyzing | Growing 🚀**

**Made by Pankaj Soni**
