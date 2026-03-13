# Diagnostic Imaging and Healthcare Infrastructure in OECD Countries

# Project Overview
This project analyzes how diagnostic imaging capacity, hospital infrastructure, and hospital stay duration have evolved across OECD countries. Using data from OECD Health Statistics, the analysis explores relationships between medical technology investment and healthcare system efficiency.
The project combines Python-based data analysis with Tableau visualization to identify trends and patterns across countries over time.

# Research Question
How does investment in diagnostic imaging technology relate to hospital infrastructure and healthcare efficiency across OECD countries?

# Hypothesis
Increased diagnostic imaging capacity is associated with expanded healthcare infrastructure while contributing to shorter hospital stays and improved healthcare system efficiency.

# Dataset
Variables used:
* CT scanners per million population
* Hospital beds per 1,000 population
* Average hospital stay length
* Country and year indicators
Dataset link:
https://www.kaggle.com/datasets/babyoda/healthcare-investments-and-length-of-hospital-stay/data

# Tools Used
* Python (Pandas, Seaborn, Matplotlib)
* Jupyter Notebook
* Tableau
* GitHub

# Analysis Workflow
* Data cleaning and dataset merging
* Time-series analysis of healthcare infrastructure
* Correlation analysis between CT Scanners and hospital beds
* Outlier detection and exploration
* Cluster analysis of healthcare system types
* Dashboard visualization in Tableau

# Key Findings
### Technology Growth
* CT scanner availability increased significantly across OECD countries from 1990–2018, reflecting growing investments in diagnostic imaging technology.
### Infrastructure Relationship
* Countries with higher CT scanner density tend to maintain greater hospital bed capacity, suggesting healthcare modernization expands both technology and infrastructure.
### Healthcare System Types
* Cluster analysis identified three distinct healthcare system models across OECD countries based on diagnostic technology investment and hospital infrastructure levels.
### Overall Insight
* OECD healthcare systems appear to be evolving toward technology-enabled efficiency, where advanced diagnostic capabilities complement rather than replace traditional hospital infrastructure.

# Visualizations
### Healthcare infrastructure Trends
<img width="1265" height="868" alt="Screenshot 2026-03-13 at 2 29 38 PM" src="https://github.com/user-attachments/assets/60ca26c2-8eda-40f2-82de-cabdf084c362" />

### CT Scanners vs Hospital Beds
<img width="954" height="861" alt="Screenshot 2026-03-13 at 2 26 07 PM" src="https://github.com/user-attachments/assets/c3b59895-5efc-4801-90aa-58e79d7d54de" />

### Healthcare Systems Clusters
<img width="889" height="871" alt="Screenshot 2026-03-13 at 2 26 30 PM" src="https://github.com/user-attachments/assets/d00130a7-18a5-4b88-a987-2a0b67e3f14b" />

# Tableau Dashboard
### Interactive dashboard avaliable here:
https://public.tableau.com/views/A6OCEDFinalProject/FinalStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Limitations
* Dataset avaliable only through 2018
* MRI units values contained inconsistencies and were excluded from the analysis

# Reproducing This Analysis
Follow the steps below to reproduce the analysis
### 1. Clone the Repository
https://github.com/Jayyvee/Python--Diagnostic-Imaging-and-Hospital-Infrastructure-in-OECD-Countries
### 2. Install Required Python Packages
Create a virtual enviroment and install dependencies
pip install -r requirments.txt
### 3. Run the Data Cleaning Script
The dataset cleaning process is located in:  /03 Scripts/Project Data Cleaning
### 4. Run the Analysis
The exploratory and statistical analysis scripts are located in: /03 Scripts/Final Project Analysis
### 5. Open the Tableau Dashboard
The final visualization dashboard is avaliable here:
https://public.tableau.com/views/A6OCEDFinalProject/FinalStory?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
### 6. Data Source
Original Data file can be found here: https://www.kaggle.com/datasets/babyoda/healthcare-investments-and-length-of-hospital-stay/data
