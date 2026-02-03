## 👋🏽 Hi, I’m Cierra

I’m a **data engineer and bioinformatics practitioner** with a strong interest in building
reproducible data pipelines, scalable analytics, and biologically meaningful models.

- 👀 **Interests:** Data engineering, bioinformatics, environmental & health data analytics  
- 🌱 **Currently learning:** ETL design, data visualization, and scalable ML workflows  
- 💞️ **Open to collaboration:** Creative or technical projects involving data, biology, or AI  
- 📫 **Contact:** ibritt.cierra@gmail.com  
- 😄 **Pronouns:** she/her  
- ⚡ **Fun fact:** I’m a plant mom who loves crocheting and painting 🌿🧶🎨  

This repository showcases hands-on projects that reflect my growth across
**AI engineering**, **data engineering**, and **computational biology**.


## 🌍🧬 Data Engineering, AI & Bioinformatics Projects

A growing portfolio of hands-on projects at the intersection of data engineering, machine learning, and computational biology.
These projects reflect my progression from data cleaning and pipeline design to interactive analytics, bioinformatics modeling, and scalable ML workflows.

🔧 Core Skills Demonstrated

- Data Engineering: data cleaning pipelines, schema design, reshaping (LONG/WIDE), reproducible workflows
- AI / ML Engineering: feature selection, logistic regression, model evaluation, Spark MLlib
- Bioinformatics: DNA/RNA sequence analysis, recurrence modeling, microbiome analytics
- Visualization & Analytics: R Shiny dashboards, geospatial mapping, correlation analysis
- Tools & Languages: Python, R, PySpark, Apache Spark, pandas, Shiny, Leaflet

## 📁 Project Overview
# 🌬️🦠 Air × Microbiome Dashboard Map
📂 air_microbiome_dashboard_map/

An interactive R Shiny application for exploring relationships between air pollution exposure and nasal microbiome composition across time and geography.

What this project demonstrates

- End-to-end analytical dashboard design
- Geospatial visualization with Leaflet
- Correlation analysis across biological and environmental domains

Key capabilities

- Genus-level and “All genera” microbiome exploration
- Interactive pollution × microbiome correlation plots
- Pearson, Spearman, and Kendall correlations with statistical readouts
- Heatmaps for pollutant and microbiome intensity
- Dynamic filtering by year, genus, pollutant, and metric

🔗 Live App: https://cierrab2319.shinyapps.io/air-micro-explorer/

Skills grown

- Translating multi-omics questions into interactive analytics
- Combining environmental health data with microbiome datasets
- Statistical reasoning and visual storytelling

# 🧹🌫️ Cleaning & Formatting EPA Air Quality Data
📂 cleaning_air_data/

A Python-based data engineering toolkit for cleaning, filtering, and reshaping EPA AQS air quality datasets (PM₂.₅, PM₁₀, NO₂).

Included scripts

- pollution_data_cleaner_gui.py
  - GUI-driven cleaning tool for raw EPA CSVs
  - Adds sample IDs and pollutant labels
  - Supports geographic filtering (state, city, county, CBSA, coordinates)
  - Outputs clean, analysis-ready CSVs
- format_by_location.py
  - Reshapes cleaned data into LONG (tidy) or WIDE (dashboard-ready) formats
  - Groups by state, city, site, CBSA, or custom keys
  - Exports to CSV or Excel (multi-sheet)

Skills grown

- Real-world data preprocessing and validation
- Building user-friendly data tools (GUI + CLI)
- Designing reusable data pipelines for analytics and dashboards

# 🩺📊 Diabetes Prediction with Apache Spark
📂 diabetes_prediction/

A machine learning project using PySpark and Spark MLlib to predict diabetes outcomes using logistic regression.

What this project demonstrates

- Distributed ML workflows using Apache Spark
- Feature selection and preprocessing at scale
- Model training, evaluation, and persistence

Key components

- Data ingestion and cleaning in Spark
- Logistic Regression model using Spark MLlib
- Model performance evaluation
- Save/load trained models

Skills grown

- Scalable ML engineering with Spark
- Transitioning from pandas-based ML to distributed systems
- Understanding production-oriented ML workflows

# 🧬 Rosalind Bioinformatics Practice
📂 rosalind/

A collection of foundational bioinformatics algorithms implemented in Python using problems from Rosalind.

Completed exercises

- count_nucleotides.py — DNA base frequency counting
- transcribed_dna.py — DNA → RNA transcription
- complement_dna.py — reverse complement generation
- recurrence_rabbit.py — population growth via recurrence relations

Skills grown

- Algorithmic thinking in computational biology
- DNA/RNA sequence manipulation
- Translating biological rules into clean, testable code

# 🚀 How These Projects Fit Together

These projects reflect a progressive skill trajectory:

- Data engineering foundations → cleaning, reshaping, and validating environmental datasets
- Analytics & visualization → turning complex data into interpretable dashboards
- Bioinformatics fundamentals → sequence analysis and biological modeling
- AI/ML engineering → scalable machine learning with Spark

Together, they support my growth toward roles in:

- AI / ML Engineering
- Data Engineering
- Bioinformatics & Computational Biology
- Environmental & Public Health Analytics

# 📌 Next Steps (In Progress / Planned)

- Integrating cleaned air quality data directly into microbiome dashboards
- Expanding microbiome analysis to higher taxonomic levels
- Applying ML models to environmental–biological interaction data
- Building reproducible pipelines for multi-omics analytics

⭐ If you’re reviewing this repository: thank you for taking the time — each folder represents an intentional step in building production-ready, interdisciplinary technical skills.
<!---
cierrak18/Bio_Projects is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
