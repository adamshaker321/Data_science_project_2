# AbeBooks Data Analysis Project

A complete **Data Analysis** project using Python, aimed at understanding the book market on **AbeBooks** and analyzing factors affecting book prices and seller behavior.

## Project Stages

### 1. ETL (Extract → Transform → Load)
- **Extract:** Collecting data from AbeBooks using `Requests` and `BeautifulSoup`.
- **Transform:** Data cleaning, handling missing values, removing duplicates, converting text columns to numeric values, splitting some columns to extract additional information (e.g., seller country), and creating a new feature `total_price = price + shipping`.
- **Load:** Saving the cleaned data into a CSV file for further analysis.

### 2. EDA (Exploratory Data Analysis)
- Exploring the distribution of book prices.  
- Analyzing the relationship between book condition, cover type, and price.  
- Studying the number of books across publication years.  
- Distribution of books by seller countries.  

### 3. Visualization
- Creating a dashboard using `Matplotlib` to display:
  - Histogram for price distribution
  - Bar/Line charts for different factor analysis
  - Pie chart for books distribution by cover type
- Quick insights like maximum price, average price, and total available quantity.

## Tools Used
- Python
- Pandas
- NumPy
- BeautifulSoup
- Requests
- Matplotlib
