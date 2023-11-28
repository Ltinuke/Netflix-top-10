# Netflix-top-10
## Table of Contents
* Objective
* Methods Used
* Tools / Techniques
* Project Requirements
* Findings / Results
## Objective
In this Netflix Data Analytic project, I used SQL to answer key investor questions based on the weekly Top 10 Netflix Data. Each week, Netflix publishes its top 10 titles, along with the number of hours spent watching each one. 
These are split up into four categories: Films(English), Films (Non-English), TV (English) and TV (Non-English). Some investor questions about Netflix that this data can help address are: Is Netflix producing and licensing engaging content? 
Are Netflix's content investments in new genres or geographies generating significant viewership? How is viewership trending over time and what implications does it have over subscriber numbers? 

## Methods Used
* Data Collection
* Exploratory data analysis
* Data Visualization
## Tools / Techniques
* SQL
* Tableau
## Project Requirements
1. Identify the TV show (English) with the most appearances in the top 10 list (you can treat each row in the data as a separate appearance). What were the average weekly viewed hours for that show across all appearances?
2. For the "Films (Non-English)" category, identify the film with the lowest IMDb rating. What were the average weekly hours viewed for that film?
3. Identify the film in the “Films (English)” category with the most cumulative weeks in the top 10. How could you approximate how many users watched this show? What assumptions would you make? What risks are there to your approach?
4. Plotting weekly hours viewed over time (as an aggregate and for each of the four categories), what are the trends?
5. Another key investor question is how many US subscribers Netflix has each quarter. Name one type of dataset you could use to answer this question. How would this data source help estimate Netflix's US subscribers?
## Findings / Results
1. The English TV show with the most appearances in the Top 10 list is **You** with an average weekly hour of **43,193,333 hours** viewed
2. The Non-English film with the lowest IMDb rating is **Nobody Sleeps in the Woods Tonight 2** with an average weekly hour of **4,610,000 hours** viewed
3. In the English film category, **Red Notice** showed up the most in the top 10 Netflix list with a cumulative of **13 weeks** in the top 10 chart. In calculating the approximate users that watched this film, I took the aggregate of the film hours viewed, multiplied it by 60 to keep it in the same unit as running time (minutes), and then divided it by the running time of the film. I would assume that approximately **228,762,711** users watched this film. This data point might **not be indicative of the unique users** because there might be users who watched multiple times.
4. On average, the **TV(English)** category has the **most weekly hours viewed** in the top 10 list. **October 2021**, has the **highest number of total weekly hours viewed** with over 5 billion hours viewed. **Films (Non-English)** is the category with the **least weekly hours viewed** every month. Users watch **more English films and TV shows** than they watch non-English ones. In the **non-English category**, users spend **more weekly hours watching the TV shows** than they spend watching the films. **March 2022** has the **least number of weekly hours viewed** across the dataset. This could be because March only has **one week of data collected**. On average, **the cooler months** (apart from November and December which have major holidays) **have higher weekly hours viewed** than the warmer months.
![image](https://github.com/Ltinuke/Netflix-top-10/assets/48940453/544df61c-3899-4349-a423-7b575dd43d8a)

5. I can get information on the number of Netflix “paying streaming subscribers” per quarter in the US from Statista and use that as a proxy for the number of subscribers. However, the most reliable data source would be Netflix’s quarterly financial report.





