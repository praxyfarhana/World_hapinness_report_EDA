# World_hapinness_report_EDA
The World Happiness Report ranks countries based on their citizens’ well-being, analyzing factors like gdp, social support, life expectancy, freedom, generosity, and corruption to provide insights into global happiness trends.

## Project Structure
- **Project Setup & Data Ingestion**
- **Data Preprocessing & Standardization**
- **Exploratory Data Analysis (EDA) - Performed for Each Year (2015-2019)**
- **Analysis and Storytelling**
- **Tools & Technologies Used**

## Dataset Composition
- 2015.csv - 158 countries, 12 columns
- 2016.csv - 157 countries, 13 columns
- 2017.csv - 155 countries, 12 columns
- 2018.csv - 156 countries, 9 columns
- 2019.csv - 156 countries, 9 columns

## Data Importing & Preprocessing
- Data Ingestion : Loaded the datasets from a zip file stored in Google Drive
- Extract Data : Extracted the compressed archive to access the CSV files
- Load Datasets : Identified the CVS files and loaded them as dictionaries where I easily accesed them
- Data Standardization : Transformed all the variable names into a uniform format for consistency:
    **Convert to Snake Case**:standardizing all column names to lowercase with underscores
    **Map to Unified Names**:
    **Apply Standardization**:

## Project Exploratory Analysis - Performed for Each Year (2015-2019)
### Basic Data Understanding:
- Inspection of the first and last few rows (head(), tail()).
- Checking dataset structure (info()) and dimensions (shape).
- Validation of data types and checking for numeric-looking strings in object columns.
  
### Descriptive Statistics & Univariate Analysis:
- Generation of summary statistics (describe()) for all numerical variables.
- Creation of histograms with KDE plots to visualize the distribution of each numerical variable.
- Calculation of skewness and kurtosis to quantitatively assess distribution shape.
- Creation of boxplots to visualize spread and identify potential outliers.
- Explicit identification and counting of outliers using the IQR method.
  
### Categorical Variable Analysis:
- Analysis of the region and country columns using value counts and bar charts.
- Visualization of the number of countries per region and the top 20 happiest countries for the year.

###  Bivariate & Multivariate Analysis:
- Creation of scatter plots with regression lines to visualize the relationship between each factor and the happiness_score.
- Calculation of a correlation matrix to quantify the relationships between all variables.
- Visualization of the correlation matrix using a heatmap.
- Identification of the strongest positive/negative correlations and checks for multicollinearity (highly correlated predictor variables).

###  Analysis and Storytelling
- After each analytical step (e.g., distributions, outliers, correlations), a clear and concise narrative interpretation is provided.

### Tools & Technologies Used
- Python
- pandas, numpy for data manipulation.
- matplotlib, seaborn for data visualization.
- zipfile, os for file handling.

### Connect
If you're passionate about data analytics, global trends, or Exploratory Data Analysis, I'd love to connect and exchange insights.
