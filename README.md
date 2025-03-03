# **IMDB Movie Analysis**

## **Objective**  
This project explores and analyzes the IMDB Movies dataset to uncover insights into movie trends, genre popularity, and factors influencing movie success. Using Python and libraries like **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**, the analysis answers specific business questions and delivers actionable recommendations to help IMDB better understand its data.

---

## **Dataset**  
The dataset used in this analysis is available at:  
[IMDB Movies Dataset](https://drive.google.com/file/d/1lruT50ZWD4PtvDbIn4VnepZvSoeO9BrA/view?usp=sharing)  

Analysis Summary Link : 
https://docs.google.com/document/d/1X6Hy1KSsvCyovFm46JS9mvMUTsUnCGTb/edit

Each row in the dataset represents a movie, and the columns include attributes like budget, revenue, genre, ratings, and release year.

---

## **Key Libraries Used**  
1. **Pandas**: For data manipulation and cleaning.  
2. **NumPy**: For numerical operations and handling missing values.  
3. **Matplotlib**: For creating static visualizations.  
4. **Seaborn**: For advanced statistical visualizations.  

---

## **Steps and Questions Addressed**  

### **1. Data Overview and Basic Exploration**  
- Used `.info()` to examine data types and missing values.  
- Generated summary statistics using `.describe()` to understand numerical columns.  
- Identified potential data quality issues like missing values, incorrect data types, or outliers.  

### **2. Data Cleaning**  
- Handled missing values appropriately, depending on their significance.  
- Converted data types, such as dates and numeric fields, for accurate analysis.  
- Addressed outliers in numerical columns like budget and revenue.  

### **3. Univariate Analysis**  
- Analyzed the distribution of scores using histograms.  
- Identified the most common genres using bar charts.  

### **4. Bivariate Analysis**  
- **Budget vs. Revenue**: Used scatter plots to explore their relationship.  
- Analyzed how ratings vary by country using box plots.  
- Calculated correlation coefficients to determine relationships between scores, budgets, and revenues.  

### **5. Genre-Specific Analysis**  
- Determined the genre with the highest average rating.  
- Visualized the popularity of genres over time by plotting the number of movies released per genre each year.  

### **6. Year and Trend Analysis**  
- Examined how average movie ratings have changed over the years using line plots.  
- Identified years with the highest and lowest movie releases using bar plots.  

### **7. Multivariate Analysis**  
- Identified the most popular genres in each decade using bar plots.  
- Analyzed the relationship between genre, release year, and average ratings.  

---

## **Key Insights**  
1. **Genre Popularity**: Some genres consistently perform better in terms of ratings, while others dominate in terms of frequency.  
2. **Budget and Revenue Relationship**: A positive correlation exists between a movie's budget and its revenue, with high-budget movies generally earning more.  
3. **Trends Over Time**: Average ratings and genre popularity have varied significantly over the decades.  

---

## **Future Exploration**  
- Investigate the impact of directors, actors, or production studios on movie success.  
- Analyze geographic trends in movie ratings and revenues.  
- Examine the effect of runtime on audience satisfaction and ratings.  
