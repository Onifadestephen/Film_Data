# Project name:Film_Data


### **Exploratory Data Analysis on Film Data Using PostgreSQL and Power BI**  
**Author**: Onifade Stephen  
**Date**: 2024-11-26  

---

## **Project Description**  
This project is an exploratory data analysis of the "film" database, which contains information about films, people, reviews, and roles. The goal is to retrieve, filter, and analyze this data to answer real-life business questions related to the film industry.  

The analysis utilizes:  
- **PostgreSQL**: For data querying and transformation.  
- **Power BI**: For data modeling, visualization, and dashboard creation.  

### **Workflow Summary**  
1. Imported the provided database dump file into PostgreSQL.  
2. Connected PostgreSQL to Power BI using a local server.  
3. Analyzed the data to solve predefined business questions.  
4. Created dashboards and KPIs in Power BI to visualize insights.  

**Disclaimer**:  
This is a fictional project created for learning purposes to demonstrate proficiency in PostgreSQL and Power BI.  

---

## **Problem Statement**  
The goal of this analysis is to answer the following business questions using PostgreSQL and Power BI:  

1. **Highest-Grossing Films**:  
   - What are the top 10 highest-grossing films in the database, and when were they released?  

2. **Film Releases by Country**:  
   - How many films in the database were released in each country, and what are the top five countries?  

3. **Languages Represented**:  
   - How many films are available in each language, and what are the top three languages represented?  

4. **IMDb Score**:  
   - What is the average IMDb score for films in the database?  

5. **Highest Profit by Country**:  
   - Which country has made the highest profit from movies? *(Using average profit to avoid bias.)*  

6. **21st Century Highest Profit**:  
   - Which movie made the highest profit in the 21st century?  

7. **People Still Alive**:  
   - How many people in the database are still alive (based on birthdate and death date)?  

8. **Year with Most Releases**:  
   - Which year has the highest number of movie releases?  

9. **Top Roles in Database**:  
   - Who are the top 10 people with the most roles in the database?  

10. **Actors/Directors with Most Roles**:  
    - Who are the top 10 actors or directors with the most roles?  

11. **People Still Alive**:  
    - Identify how many people in the database are still alive.  

12. **Reviews Analysis**:  
    - Calculate the average number of user and critic reviews for films.  

13. **Films with Most Reviews**:  
    - Identify films with the highest number of user and critic reviews.  

14. **Facebook Likes vs IMDb**:  
    - Which films have the most Facebook likes, and is there a correlation with their IMDb scores?  

---

## **Tools and Techniques**  

### **PostgreSQL**  
- Utilized SQL functions and commands including:  
  - `SELECT`, `INNER JOIN`, `AVG`, `DISTINCT`, `COUNT`, `GROUP BY`, `ORDER BY`, `LIMIT`, `HAVING`, `MAX`.  
- Performed data transformation and analysis to answer business questions.
 ## Data Modeling

Power BI automatically detects and creates relationships between tables, which is convenient for quick analyses. However, as someone who understands the dataset and aims to extract specific insights, I chose to demonstrate my data modeling skills by removing the automated relationships and manually creating a custom model.

By doing so, I had full control over how the tables were related, ensuring the model aligned with the business questions and analysis goals. This approach allowed me to define precise relationships and optimize the data model for better performance and clarity.

### **Power BI**  
- Created Key Performance Indicators (KPIs) and performed business calculations.  
- Used data modeling techniques to define relationships between tables.  
- Leveraged DAX (Data Analysis Expressions) for advanced measures and calculations.  
- Built interactive dashboards with filters for an intuitive user experience.  

---

## **Data Source**  
The data used in this project was provided by Techwaconsult.  
- The schema, objects, and data dictionary were studied to understand the structure of the database.  
- Relevant tables and fields were identified for the analysis.  

---

## **Results and Insights**  

1. **Top-Grossing Films**:  
   - Identified the top 10 highest-grossing films, along with their release dates.  

2. **Film Releases by Country**:  
   - Analyzed the number of films released per country and highlighted the top five contributors.  

3. **Languages**:  
   - Highlighted the distribution of films by language and identified the top three languages represented.  

4. **IMDb Scores**:  
   - Calculated the average IMDb score for all films in the database.  

5. **Profitable Countries and Movies**:  
   - Determined the country with the highest average profit and the most profitable movie of the 21st century.  

6. **Yearly Releases**:  
   - Found the year with the highest number of movie releases.  

7. **Roles and Reviews**:  
   - Identified the top actors/directors with the most roles and films with the highest number of user and critic reviews.  

8. **Facebook Likes vs IMDb**:  
   - Investigated whether a correlation exists between Facebook likes and IMDb scores.  

---

## **Power BI Dashboard Features**  

The Power BI dashboard includes:  
- **Creating key performance indicators (KPIs) and other business calculations** 
- **Filters**:release Year, language, country, and name.  
- **Visualizations**:  
  - average profit by country
  - count of title by country  
  - max of gross by title
  - count of title by langyage
 
 
## Recommendations Based on Film Data Analysis

Based on the data and visuals provided in the dashboard for the exploratory data analysis on film data, here are some key recommendations for optimizing film production and distribution:

### 1. Focus on High-Grossing Markets

- **USA Dominance**: The USA dominates the count of titles, suggesting it is a primary market for film production and distribution. Increasing investment in U.S.-based productions or targeting U.S. audiences could yield higher returns.
- **Explore High-Profit Countries**: Countries like New Zealand and Taiwan show high average profits, despite having fewer titles. Exploring collaborations or creating content suited to these regions may enhance profitability.

### 2. Diversify Content by Language

- **English Dominance**: English is the most common language in the dataset, but other languages like Spanish and Mandarin represent untapped potential for growth. Expanding multilingual content could help attract larger international audiences and increase viewership.

### 3. Leverage Successful Genres or Titles

- **Blockbuster Potential**: Top-grossing films such as *Avatar* and *Titanic* highlight the importance of blockbuster productions. Investing in films with large-scale production values, proven directors, or franchise potential could maximize returns.

### 4. Target Underrepresented Years or Trends

- **Focus on Recent Trends**: The dashboard spans release years from 1916 to 2016, but modern production trends or popular genres may be more relevant. Analyzing the past 10 years of data to identify emerging trends or audience preferences can refine production strategies and improve profitability.

### 5. Explore Specific Country Opportunities

- **Untapped Regional Markets**: Countries with fewer titles, such as Peru or other regions in South America, may present growth opportunities. Producing culturally relevant content for these regions could attract new audiences and increase market share.

### 6. Capitalize on Niche Opportunities

- **Niche Audiences**: Films in specific languages or from underrepresented countries might appeal to niche audiences who are willing to pay a premium for culturally relevant content. This could be a profitable strategy for both streaming platforms and theaters.

### 7. Optimize User Experience

- **Leverage User Data**: With the average number of users per metric being 275.7, a better understanding of user preferences through social media insights or streaming services can help align production with audience demand. Personalization and targeting specific demographics can enhance viewership.






