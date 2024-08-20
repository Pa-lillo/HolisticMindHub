# Data Analyst | Data Scientist

### Technical skills: Python, SQL, Tableau, Excel, R, Cloudera Impala, Vertica

## Education 
- B.Sc., Neuroscience | National Autonomous University of Mexico (UNAM) (_2019-2023_)

## Experience
**Consultant - Intelligence & Data Analytics @ Banco Azteca, Grupo Salinas (_Feb 2024 - Present_)**
- Implemented an unsupervised clustering algorithm to create client profiles, enabling the development of targeted campaigns to increase transactions and income.
-  Developed an early warning system in Python, leveraging statistical analysis to monitor KPIs and significantly boost profits.
- Managed the Intelligence & Data Analytics area, providing crucial analytical support to enhance business unit initiatives and campaigns.
- Generated and maintained reports and dashboards in Tableau, ensuring data-driven decision-making through accurate KPI tracking.
- Automated and optimized data workflows for large datasets, improving efficiency and reducing manual processes using R, SQL, and Python.
- Collaborated with cross-functional teams to implement innovative data solutions, driving overall business performance.
- Presented actionable insights to directors and managers, translating complex data into clear strategies.

**Data Research Assistant @ Quantitative Biology Laboratory, IBFG-CSIC (_May 2023 - December 2023_)**
- Led a data science project, implementing machine learning models for classification tasks and developing a user-friendly Python GUI to streamline processing.
- Authored and directed a research paper, effectively communicating results and visualizations to the scientific community.
  
**Research Intern @ National Institute of Psychiatry Ramón de la Fuente Muñiz (_January 2022 - May 2023_)**
- Enhanced laboratory processes by developing a script for streamlined plotting protocols and managing data in Excel.
- Conducted mouse surgeries and analyzed electroencephalogram recordings using MATLAB, Prism, and SPSS.

## Projects
### Client Clustering for Airtime Recharge Optimization
**Tools: Python, SQL, Pandas, Dask, Scikit-learn, Data Mining, Mathematical Modeling**
- _Objective_: To segment clients based on their airtime recharge behavior and develop targeted campaigns to increase recharge frequency, thereby boosting company revenue.
- _Data Extraction_: Performed data mining using SQL to extract 30 million records of telephone numbers, recharge amounts, recharge dates, and mobile operators from the database.
- _Data Preparation_: Conducted data wrangling using Pandas and Dask to clean and prepare the dataset, including the calculation of recharge frequency, a critical variable not originally present.
- _Exploratory Data Analysis_: Utilized descriptive statistics and frequency distributions to gain insights into client behavior and guide model selection.
- _Model Implementation_: Applied the K-means clustering algorithm using Scikit-learn, which resulted in the identification of four distinct client clusters.
- _Revenue Modeling_: Developed a mathematical model to project potential revenue increases by applying different conversion rates to each client cluster based on their recharge patterns.
- _Outcome_: The clustering and subsequent analysis provided the business with targeted insights to tailor campaigns, thereby enhancing client engagement and increasing recharge activity across all major mobile operators.

### Early Warning System for KPI Monitoring
**Tools: Python, SQL, Pandas, Numpy, Tkinter, Statistical Analysis (U-Mann Whitney Test)**
- _Objective_: To develop an advanced early warning system to monitor and compare key performance indicators (KPIs) such as transactions, amount, and income across different business units in order to identify significant deviations from the previous year's data and provide early notifications of potential issues.
- _Data Comparison_: The system was designed to compare accumulated data for each week of 2024 to the corresponding week of 2023.
- _Percentage Change Calculation_: The system calculates the percentage change for each KPI between the two years. If the difference exceeds a predefined threshold (usually 50%), the system flags this in the early warning dashboard, indicating that the particular field requires attention.
- _Statistical Significance Testing_: To ensure that the observed differences were not due to random variation, the U-Mann Whitney statistical test was applied. This non-parametric test compared the weekly distributions of the KPIs from both years, allowing to assess whether the differences were statistically significant (using the P-value).
- _Weekly Streak Calculation_: The system also tracked the weekly streak of each field, calculating how many consecutive weeks a particular field had shown a similar trend (either positive or negative). This feature helped in identifying persistent trends that required intervention.
- _GUI Development_: All the functionalities were integrated into a user-friendly Graphical User Interface (GUI) developed using Python's Tkinter library. The GUI provided easy access to the early warning system, enabling business users to quickly identify and address issues without needing to dive into complex data analysis.
- _Data Handling_: SQL was used to extract relevant data from the database, Pandas for data import and manipulation within Python, and Numpy for performing the necessary calculations.
- _Outcome_: This early warning system significantly enhanced the company's ability to proactively manage its operations, allowing for quicker responses to emerging trends and contributing to the company’s overall profitability by preventing potential losses and identifying growth opportunities in real-time.

### Strain Classification of Fission Yeast using Machine Learning
_Set to be published soon_

Spearheaded a scientific article focusing on the application of data science and machine learning to classify strains of fission yeast, covering both control and mutant strains. Managed tasks such as data cleaning, strain selection, and hyperparameter tuning using **Python**. The methodology included processing microscopy movies, extracting various features, and evaluating machine learning models. The Random Forest model excelled in binary classification, leading to its selection for multiclass classification. The project achieved over 75% accuracy in categorizing strains and underwent successful testing with new data. Contributed to drafting the scientific article, emphasizing methodology, results, and discussion. The ultimate goal is to translate this methodology for broader applications in different experimental models and labs.

![Fission yeast](/assets/img/Fission_yeast.jpg)

### Enhancing Lab Protocols with a GUI
[Jupyer Notebook](https://github.com/Pa-lillo/HolisticMindHub/blob/main/Projects/GUI4Lab/UI4ChroMo.ipynb)

[Identifying Chromosome Movement Patterns During Meiosis Using ChroMo](https://pubmed.ncbi.nlm.nih.gov/39126481/)

Played a pivotal role in translating **R** scripts to **Python**, utilizing tkinter to create a Graphical User Interface (GUI) that offered diverse approaches, significantly improving the user-friendliness of the lab protocols and streamlining the methology. Further contributed to writing the methodology, results, and figures for a book chapter on computational methods. The outcome was a more accessible and efficient protocol, showcasing the fusion of technical translation and scientific communication to advance computational capabilities in the lab.

![GUI for Lab Protocol](/assets/img/UI4Chromo.png)


### Python Script for EEG Data Processing and Visualization
[Jupyer Notebook](https://github.com/Pa-lillo/HolisticMindHub/blob/main/Projects/EEGVisualization/PlotEEGRelativePower_Smooth.ipynb)

Developed a versatile **Python** script featuring distinct functions designed to seamlessly import, preprocess, apply a Savitzky-Golay filter, compute errors, and generate visualizations from **Excel** data. The primary objective was to produce a relative power (EEG) plot with smoothing. The protocol is acknowledged in a [published research paper](https://www.sciencedirect.com/science/article/abs/pii/S0378874122005311?via%3Dihub).

![Human EEG](/assets/img/eeg_human.webp)

###  Exploratory Data Analysis and Prediction of Lego Set Trends
[Jupyer Notebook](https://github.com/Pa-lillo/HolisticMindHub/blob/main/Projects/LegoSetsAnalysis/LegoThemesProject.ipynb)

Conducted a comprehensive analysis of Lego sets spanning from 1950 to 2017 utilizing **Python**. The process encompassed data exploration, cleaning, visualization, and analytical tasks. Specific analyses included determining the percentage of licensed sets, identifying the most popular sets by year, assessing the number of unique sets, and calculating the average number of blocks released annually. The project culminated in the implementation of a polynomial regression model to predict the number of unique sets and average blocks expected for the years 2018-2030.

![LEGO](/assets/img/lego_blocks.jpg)
