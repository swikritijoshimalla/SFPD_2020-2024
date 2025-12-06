# SFPD_2020-2024
San Francisco Police Department (SFPD) incident reports (2020-2024) to identify, visualize, and forecast crime patterns across city neighborhoods.

**About the Project**
This capstone project analyzes five years of San Francisco Police Department (SFPD) incident reports (2020–2024) to identify, visualize, and forecast crime patterns across city neighborhoods. Although seven years of data were available, the most recent five were selected for relevance and accuracy. The project aims to uncover cyclical trends in crime frequency and location to support data-driven public safety planning and promote informed community decision-making.

Using tools such as Python, ArcGIS, Tableau, and statistical modeling, the team examines how factors like time of day, season, and neighborhood characteristics influence crime activity. Predictive modeling techniques—including clustering and regression analysis—are applied to forecast high-risk zones and evaluate how patterns shift over time. Exploratory Data Analysis (EDA) combines visualizations and correlation mapping to highlight relationships between crime types, time, and geography, while ethical frameworks guide the project to ensure fairness, transparency, and accountability in interpreting policing data.

The project deliverables include an in-depth research paper, interactive ArcGIS maps, and visual dashboards that make the findings accessible to both technical and public audiences. These tools are designed to encourage dialogue on equity, safety, and the responsible use of data science in urban policy and management.


**Project Team**
This capstone project was developed by Eduardo Rosas and Swikriti Joshi, graduate students in the Big Data Analytics program at San Diego State University. Their shared goal is to apply data science and visualization techniques to real-world challenges, using open data to promote transparency, ethical analysis, and community engagement.

**Spatial-Temporal Crime Prediction and Socioeconomic Modeling in San Francisco (2020-2024)**
**Team:** SF Terabytes - Eddie Rosas & Swikriti Joshi
**Affiliation:** San Diego State University, Big Data Analytics (BDA 600 Capstone Seminar)
**Instructors:** Dr. Gabriela Fernandez & Dr. Ming-Hsiang Tsou
**Project Website:** SFPD 2020–2024 Crime Project
**Contact:** erosas9172@sdsu.edu (Eddie) · sjoshi2639@sdsu.edu (Swikriti)

This capstone project investigates how crime patterns evolve across San Francisco by integrating five years of incident-level data (2020–2024) with machine learning, time-series forecasting, and geospatial modeling. The goal is to understand when and where crime risk increases, and how temporal cycles, district-level patterns, and routine-activity trends can support fair, data-informed public safety planning.

The analysis combines Python-based machine learning (Decision Trees, SARIMAX, Prophet), ArcGIS spatial processing, and dashboard visualization. Daily crime counts were used to train a Decision Tree classifier that predicts high-incident days, achieving a Macro-F1 score of approximately 0.61 and ROC-AUC ≈ 0.65. For short-term forecasting, citywide daily totals were modeled using Prophet and SARIMAX, with Prophet obtaining a MAPE of 8.6% and producing stable 30-day forecasts capturing strong weekly and yearly seasonal cycles.

Spatially, incidents were aggregated at the police district level and joined to official district boundaries, enabling district-level comparisons and hotspot identification. These spatial and temporal outputs were integrated into an ArcGIS Dashboard that visualizes district-level risk, historical patterns, and forecast summaries in an interactive and accessible format intended for both public users and decision-makers.

Throughout the project, we emphasized transparency, interpretability, and ethical considerations. While predictive models can support public safety efforts, they also present risks related to bias, data quality, and public perception. Our framework highlights responsible use: predictions are designed to inform community-focused planning, not punitive enforcement. Together, the classification model, forecasting pipeline, and spatial dashboard create a unified, reproducible system for understanding crime dynamics in San Francisco.
