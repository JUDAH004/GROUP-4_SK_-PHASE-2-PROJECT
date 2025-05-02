# MOVIE MARKET ANALYTICS
## Overview
This project analyzes data from leading movie industry sources to uncover data-driven insights that will guide our company in launching a successful movie studio.The goal is to identify top-performing genres and emerging trends at the box office. By leveraging these insights, the company can make informed decisions and strategically create films that are positioned for commercial success.

## Business Understanding
Our company wants to venture into the film industry but due to lack of prior experience we are faced with the following questions which are;

> **What type of films are most likely to succeed at the box office?**
> **What trends at the box office are associated with successful films?**

Therefore,every process done in this project aims to answer the questions above.

## Data understanding and analysis
### Datasets
The project utilises data sourced from the following websites;
> **Internet Movie Database(IMDb)**
> **Rotten Tomatoes**
> **Box office Mojo**
> **The Numbers**
> **The MovieDb**

## Methodology : Approach to Film Industry Analysis
To ensure thorough breakdown of the problem at hand, the project notebook shall follow the following structure;
1. **Data Exploration**
- Here the datasets will be loaded and examined to know their structure(number of columns and rows) ,the type of data in them.
- Checking of missing values and duplicated values is done in this stage.
- Descriptive statistic like min/max values will also be carried out for columns with numerical values.
2. **Data Cleaning**
- Handling of missing values through removal where necessary.
- Removing of duplicated rows
- Filtering the data by removing unneccessary columns that will not help us in our analysis.
3. **Data visualization and Analysis**
- Generation of useful visualizations to determine the trends in the industry.
- Check for relationships between different variables in the datasets.
- From this stage we can know whether or not to reject the Null Hypothesis.
4. **Business Recommendations**
- Finally from following the above steps when working with the datasets, we can insighfully
recommend concrete data-driven recommendations to support the success of the new movie studio.

## Key Visualizations
Visualizations presented in this project:
1. **Top Performing Studios by Worldwide Gross**
![ddf0c619-2139-4767-a736-1d983693333a](https://github.com/user-attachments/assets/02557c54-a62f-4160-a3ba-01730e61ea62)

2. **Domestic vs. Foreign Revenue**
![85f646d4-61ae-4fd7-b99b-f18e2d00026c](https://github.com/user-attachments/assets/8f31c56a-21a4-4cff-a6a4-3a1a06f4cbfe)

3. **Top Genres by Worldwide Gross**
![1cc42eab-1b3b-4f28-9340-e3f3c77e734b](https://github.com/user-attachments/assets/f26a5fac-9f2a-4a5b-bade-cfe3ef7b8500)

4. **The Most Popular Genre(The Movie DB)**
 ![e687521d-632e-42f0-81fb-b146968be41a](https://github.com/user-attachments/assets/f0b61abf-70ca-4042-b111-6d82ad80a421)

5. **ROI vs. Film Rating(Rotten Tomatoes)**
![eeb3e46a-1ca8-4160-a1dc-e5eb83659014](https://github.com/user-attachments/assets/86e413cd-5475-4b9e-89e1-3927da9434b2)

6. **Influence of Directors on Movie Rating(IMDB)**
![8bbf3180-c3b6-43a4-9364-bb3c090c8c7f](https://github.com/user-attachments/assets/d580ab46-b044-4652-a2c6-5ced0a5b669b)

## Tools & Technologies
The project utilizes the following tools and technologies:

### **Programming Language**
- **Python**: Used for data analysis, visualization, and statistical computations.

### **Libraries and Frameworks**
1. **Data Manipulation and Analysis**:
   - **Pandas**: For data cleaning, manipulation, and merging datasets.
   - **NumPy**: For numerical computations and handling arrays.

2. **Data Visualization**:
   - **Matplotlib**: For creating static, interactive, and publication-quality visualizations.
   - **Seaborn**: For advanced statistical data visualization.

3. **Statistical Analysis**:
   - **SciPy**: For performing statistical tests like t-tests and correlation analysis.

4. **String and Data Parsing**:
   - **ast**: For safely evaluating strings containing Python literals (e.g., converting stringified lists to actual lists).

5. **Database Interaction**:
   - **SQLite3**: For querying and extracting data from SQLite databases.

6. **File Handling**:
   - **zipfile**: For extracting compressed files.
   - **os**: For file path and directory management.

### **Data Sources**
- **Box Office Mojo**: For box office revenue data.
- **The Numbers**: For movie budgets and financial performance.
- **TMDB (The Movie Database)**: For genre, popularity, and audience ratings.
- **Rotten Tomatoes**: For movie reviews and critic ratings.
- **IMDb (Internet Movie Database)**: For movie metadata, ratings, and director information.

### **File Formats**
- **CSV**: Used for storing and processing datasets.
- **TSV**: Tab-separated values for Rotten Tomatoes data.
- **SQLite Database**: For structured data storage and querying (IMDb data).

### **Statistical Techniques**
- **T-Tests**: For comparing means (e.g., domestic vs. foreign revenue, high vs. low budget ROI).
- **Pearson Correlation**: For analyzing relationships between variables (e.g., budget vs. gross).
- **Composite Scoring**: For ranking directors based on normalized ratings and votes.

### **Visualization Techniques**
- **Bar Charts**: For comparing revenue, ROI, and genre popularity.
- **Lollipop Charts**: For ranking directors by composite scores.
- **Horizontal Bar Charts**: For revenue splits and genre analysis.

### **Integrated Development Environment (IDE)**
- **Jupyter Notebook**: For interactive data analysis and documentation.

### **Data Cleaning and Preprocessing**
- Handling missing values, duplicates, and inconsistent data.
- Converting data types (e.g., dates, numeric values).
- Exploding multi-value columns (e.g., genres) for granular analysis.

These tools and technologies collectively enable efficient data exploration, cleaning, analysis, and visualization to derive actionable business insights.

📂 Repository Structure

Cleaned/ → Folder containing the extracted cleaned dataset for interactive dashboard creation with Tableau

Data/ → Folder containing datasets for analysis

images/ → Folder containing key visualizations obtained from the analysis

README.md → This document outlining project details

index.ipynb → Jupyter Notebook containing the full analysis

presentation.pdf → Presentation summarizing key insights and business recommendations for investors


