# Data Analysis | Data Science Manager

### Technical skills: Python, SQL, Tableau, Excel, R, Cloudera Impala, Vertica

## Education 
- B.Sc., Neuroscience | National Autonomous University of Mexico (UNAM) (_2019-2023_)

## Experience
**Data Intelligence & Analytics Manager @ Banco Azteca, Grupo Salinas (_Sep 2024 - Present_)**

✅ Drive Strategy with Insights
- Lead analytics team to optimize marketing and business performance.

📊 Build Dynamic Dashboards
- Design Tableau tools to monitor KPIs and enable smart decisions.

🤝 Engineer Scalable Solutions
- Collaborate across teams to deploy efficient, growth-driven systems.

📈 Influence Leadership with Data
- Present clear, actionable insights to executive stakeholders.

🗺️ Map Data for Targeting
- Develop geospatial pipelines for precise audience segmentation.

💡 Deliver Cost Savings
- Apply advanced analytics to reduce expenses while preserving value.

**Consultant - Data Intelligence & Analytics @ Banco Azteca, Grupo Salinas (_Feb 2024 - Sep 2024_)**

🧠 Enabled Targeted Campaigns
- Implemented clustering to create customer profiles, boosting transactions and revenue.

⚠️ Built Early Warning System
- Developed statistical alerts in Python, driving profit increases across business units.

🧹 Cleaned & Processed Data
- Handled large-scale wrangling in SQL, Python, and R for accurate reporting.

⚙️ Optimized Data Workflows
- Automated processes for massive datasets, improving efficiency and scalability.

**Data Research Assistant @ Quantitative Biology Laboratory, IBFG-CSIC (_May 2023 - December 2023_)**

🧪 Led End-to-End Data Science Project
- Built classification models and a Python GUI to streamline processing.

📄 Published Research Findings
- Authored and visualized results in a peer-reviewed scientific paper.
  
**Research Intern @ National Institute of Psychiatry Ramón de la Fuente Muñiz (_January 2022 - May 2023_)**

🧬 Optimized Lab Workflow
- Developed a Python script for plotting and managed data in Excel.

🧠 Conducted Neuroscience Experiments
- Performed mouse surgeries and EEG analysis using MATLAB, Prism, and SPSS.

## Projects
### Client Clustering for Airtime Recharge Optimization

**Tools: Python, SQL, Pandas, Dask, Scikit-learn, K-means, Data Mining, Mathematical Modeling**
- _Objective_: To segment clients based on their airtime recharge behavior and develop targeted campaigns to increase recharge frequency, thereby boosting company revenue.
- _Data Extraction_: Performed data mining using SQL to extract 30 million records of telephone numbers, recharge amounts, recharge dates, and mobile operators from the database.
- _Data Preparation_: Conducted data wrangling using Pandas and Dask to clean and prepare the dataset, including the calculation of recharge frequency, a critical variable not originally present.
- _Exploratory Data Analysis_: Utilized descriptive statistics and frequency distributions to gain insights into client behavior and guide model selection.
- _Model Implementation_: Applied the K-means clustering algorithm using Scikit-learn, which resulted in the identification of four distinct client clusters.
- _Revenue Modeling_: Developed a mathematical model to project potential revenue increases by applying different conversion rates to each client cluster based on their recharge patterns.
- _Outcome_: The clustering and subsequent analysis provided the business with targeted insights to tailor campaigns, thereby enhancing client engagement and increasing recharge activity across all major mobile operators.

![Clusters](/assets/img/TAClusters.png)
![Potential Income](/assets/img/TAPotentialIncome.png)

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

![GUI-EarlyWarnings](/assets/img/GUI-EarlyWarnings.jpeg)

### Fission Yeast Strain Classification using Machine Learning
_Set to be published soon_

**Tools: Python, Random Forest, Microscopy, Data Wrangling, Feature Extraction, Hyperparameter Tuning**
- _Objective_: To develop and execute a project aimed at applying data science and machine learning techniques to classify strains of fission yeast, both control and mutant strains. The ultimate goal was to establish a reliable methodology that could be adapted and applied to different experimental models and laboratories.
- _Data Preparation_: Initiated the project by carefully selecting relevant strains and cleaning the raw data to ensure accuracy and reliability. This process involved processing microscopy movies to extract meaningful features that could be used for model training. Data cleaning included handling missing values, correcting errors, and standardizing the data for consistent analysis.
- _Feature Extraction_: Implemented a pipeline for extracting diverse features from microscopy images that were crucial for distinguishing between different yeast strains. These features were derived from image properties such as shape, intensity, speed, and other relevant metrics.
- _Machine Learning Model Development_: Explored various machine learning models for the classification task, with a particular focus on binary classification. The Random Forest model was identified as the best-performing model for this task, demonstrating superior accuracy and robustness in classifying the control and mutant strains.
- _Hyperparameter Tuning_: Applied hyperparameter tuning techniques to optimize the Random Forest model, ensuring the highest possible accuracy and generalizability of the results. This step involved testing different combinations of parameters and selecting the best configuration.
- _Transition to Multiclass Classification_: Expanded the scope of the model to handle multiclass classification, where it was tasked with categorizing multiple yeast strains. The model achieved over 75% accuracy in this more complex task, successfully distinguishing between the different strains.
- _Evaluation and Validation_: The model was rigorously tested with new, unseen data to validate its performance. The high accuracy rate demonstrated the model’s effectiveness and potential for broader application.
- _Scientific Communication_: Played a key role in drafting the scientific article that documented the entire project. Focusing on detailing the methodology, discussing the results, and outlining the significance of the findings. The article also emphasized the potential for translating this methodology to other experimental models.
- _Impact and Future Applications_: The project not only provided valuable insights into yeast strain classification but also laid the groundwork for applying similar methodologies in other research areas. The success of the model in this context suggests its potential utility in a wide range of biological and biomedical research projects.

![Fission yeast](/assets/img/Fission_yeast.jpg)

### GUI Development for Enhanced Lab Protocols

[Jupyer Notebook](https://github.com/Pa-lillo/HolisticMindHub/blob/main/Projects/GUI4Lab/UI4ChroMo.ipynb)

**Tools: Python, Tkinter, R, GUI Development, Scientific Writing, Computational Methods**
- _Objective_: To translate existing R scripts into Python, with the goal of enhancing the usability and efficiency of lab protocols. The project focused on creating a Graphical User Interface (GUI) using Tkinter to make the computational methods more accessible to lab members, particularly those without programming expertise.
- _Script Translation and Optimization_: Undertook the critical task of translating complex R scripts into Python, ensuring that all functionalities were preserved or improved. This process involved a deep understanding of both programming languages and their respective libraries, allowing for a seamless transition that maintained the integrity of the original methods.
- _GUI Development_: Leveraged Tkinter to design and develop a user-friendly GUI that offered diverse approaches to the lab’s computational tasks. The GUI provided an intuitive interface for users to interact with the underlying Python scripts, significantly improving the accessibility of the lab’s computational methods. By simplifying the workflow, the GUI empowered lab members to perform complex analyses without needing extensive programming knowledge.
- _Methodology Enhancement_: Through the GUI, the lab’s methodology was streamlined and refined, reducing the complexity of data processing tasks and minimizing the potential for human error.
- _Scientific Communication_: Played a substantial role in contributing to the writing of the methodology, results, and figures for a book chapter on computational methods.
- _Outcome and Impact_: The project resulted in a more accessible and efficient protocol that not only enhanced the lab’s computational capabilities but also demonstrated the power of technical translation and scientific communication. The success of the project was encapsulated in the published book chapter, which serves as a valuable resource for other researchers seeking to implement similar methods in their own work.
- _Advancing Computational Methods_: By combining technical expertise in programming with a commitment to improving lab workflows, this project underscored the importance of interdisciplinary approaches in advancing scientific research. The GUI and translated scripts are now integral tools within the lab, contributing to more streamlined and effective research processes.

[Identifying Chromosome Movement Patterns During Meiosis Using ChroMo](https://pubmed.ncbi.nlm.nih.gov/39126481/)

![GUI for Lab Protocol](/assets/img/UI4Chromo.png)

###  Comprehensive Analysis and Forecasting of Lego Sets

[Jupyer Notebook](https://github.com/Pa-lillo/HolisticMindHub/blob/main/Projects/LegoSetsAnalysis/LegoThemesProject.ipynb)

**Tools: Python, Pandas, Data Visualization, Data Cleaning, Polynomial Regression, Predictive Modeling**

- _Objective_: To analyze the trends and evolution of Lego sets released between 1950 and 2017, focusing on key aspects such as the percentage of licensed sets, yearly popularity, unique set counts, and the average number of blocks per set. The project also aimed to forecast these trends from 2018 to 2030 using predictive modeling.
- _Data Exploration and Cleaning_: Utilized Python to import, clean, and prepare the Lego sets dataset, ensuring data accuracy by addressing missing values, inconsistencies, and outliers. This preparatory work laid a solid foundation for reliable analysis and visualization.
-_Analytical Insights_: Conducted a comprehensive analysis of the Lego sets over time, identifying key metrics such as the percentage of licensed sets and the most popular sets each year.
Assessed the trends in the number of unique sets and the average number of blocks released annually, providing insights into Lego's evolving product offerings.
- _Predictive Modeling_: Developed and implemented a polynomial regression model to forecast future trends in the number of unique Lego sets and the average number of blocks for the years 2018 to 2030. The model was trained on historical data, offering predictions to guide future expectations.
- _Visualization_: Created a series of data visualizations to represent the historical trends and forecasted outcomes clearly. These visualizations helped distill complex data into understandable insights, facilitating decision-making and strategy development.
- _Outcome and Impact_: The project provided detailed insights into the historical trends of Lego sets and offered valuable forecasts for the future, enabling stakeholders to make informed decisions based on data-driven predictions. The analysis highlighted the evolving nature of Lego's product lines, offering a comprehensive understanding of the factors influencing Lego's market presence over time.



![LEGO](/assets/img/lego_blocks.jpg)
