**Analysis-and-Prediction-of-SpaceX-Falcon-9-Landings**

**Overview**

This project involves analyzing historical SpaceX Falcon 9 launch data to uncover key factors influencing landing success and developing predictive models to forecast future landing outcomes. The project is structured into several stages, each handled by different Python files. Below is a detailed explanation of what each file accomplishes.


**Files Description**

**1. jupyter-labs-webscraping.ipynb**
Purpose: This notebook is focused on web scraping data related to SpaceX launches from online sources such as Wikipedia. The goal is to gather historical launch records that are not readily available through APIs.

**Key Tasks:**
Used Python libraries such as BeautifulSoup and requests to scrape relevant data from SpaceX-related web pages.
Extracted information on launch dates, launch sites, payloads, and outcomes.
Cleaned and stored the scraped data in a structured format for further analysis.


**2. jupyter-labs-spacex-data-collection-api.ipynb**
Purpose: This notebook demonstrates how to collect SpaceX launch data using APIs. The aim is to gather detailed and structured launch information directly from official sources.

**Key Tasks:**
Utilized SpaceX’s RESTful API to fetch data on launch details, including booster versions, payload information, launch outcomes, and landing results.
Processed and transformed the raw API data into a suitable format for analysis.
Combined the API data with the scraped data from the previous notebook to create a comprehensive dataset.


**3. jupyter-labs-eda-sql-coursera_sqllite.ipynb**
Purpose: This notebook performs Exploratory Data Analysis (EDA) using SQL queries on the combined SpaceX dataset stored in an SQLite database.

**Key Tasks:**
Loaded the dataset into an SQLite database and performed SQL queries to explore different aspects of the data.
Executed queries to extract information about launch site usage, payload distribution, mission outcomes, and customer details.
Analyzed the relationships between various features using SQL queries to uncover patterns and insights, which were later visualized using Python.


**4. edadataviz.ipynb**
Purpose: This notebook focuses on visualizing the SpaceX launch data to explore relationships and patterns using Python’s visualization libraries.

**Key Tasks:**
Created various types of plots such as scatter plots, bar charts, line charts, and pie charts to visualize key features like payload mass, orbit type, and launch success rates.
Used libraries such as matplotlib, seaborn, and plotly for generating insightful visualizations.
Analyzed visualizations to gain a deeper understanding of how different factors influence the success of Falcon 9 landings.


**5. lab_jupyter_launch_site_location.ipynb**
Purpose: This notebook utilizes Folium to create interactive maps for visualizing SpaceX launch site locations and analyzing geographical patterns.

**Key Tasks:**
Mapped the coordinates of different SpaceX launch sites using Folium.
Visualized clustering of launch sites and their proximity to strategic geographical features.
Integrated additional information such as launch success rates and site-specific details through interactive markers and pop-ups.


**6. SpaceX_Machine Learning Prediction_Part_5.ipynb**
Purpose: This notebook covers the predictive analysis part of the project, focusing on building and evaluating machine learning models to predict landing success.

**Key Tasks:**
Prepared the dataset by encoding categorical variables and normalizing numerical features.
Implemented various machine learning models including Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN).
Evaluated model performance using confusion matrices, accuracy metrics (precision, recall, F1-score), and ROC curves.
Analyzed feature importance to identify which factors most influence landing success.


**Conclusion**
This project combines web scraping, API data collection, SQL-based exploratory analysis, interactive data visualization, and machine learning to provide a comprehensive analysis of SpaceX Falcon 9 launch success. The insights gained from this analysis can support decision-making processes, optimize launch operations, and enhance the reliability of future missions.


**How to Use**
Clone the repository to your local machine.
Open each Jupyter notebook in the order provided to follow the complete analysis workflow.
Install necessary Python libraries and dependencies listed in the requirements.txt file.
Run the notebooks to reproduce the analysis, visualizations, and predictive models.

**Requirements**
Python 3.x
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, plotly, folium, sklearn, sqlite3, BeautifulSoup, requests

**Author**
Mahendhar Mittapally with support of IBM learning
