# Google-Sheets-NY-citi-bike 🚴

**Background** 

 Citi Bike is the largest bike-share program in the United States, with 20,000 bikes and over 1,300 pick-up stations across Manhattan, Brooklyn, Queens, the Bronx, and Jersey City. As stated on their website, the service was designed for quick trips with convenience in mind, offering a fun and affordable way to get around town. Users can sign up for annual membership, or buy a short-term pass through the Citi Bike app. Once they’ve joined, they simply locate a nearby bike, ride around as they please, and return it to a nearby station once they’re done 

### [Final Presention Slides](https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/NY%20Citi%20Bike%20Analysis.pdf)

***

**Assigment**

Your mission is to analyze data collected by Citi Bike and help key stakeholders to make smart, data-driven decisions based on the insights you uncover. Here’s what you’ll seek to investigate:

 1. What are the most popular pick-up locations across the city for NY Citi Bike rental?
 2. How does the average trip duration vary across different age groups?
 3. Which age group rents the most bikes?
 4. How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week?
 5. Does user age impact the average bike trip duration?
***
## **Data Cleaning** 

Here is a visual of the source data set before cleaning 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Ny%20unclean.png" >

We’ve established how important the data cleaning stage is. To clean the data, I completed the following: 
- Delete unnecessary columns 
- Remove duplicates **3555 rows removed** 
- Deal with missing data **3 rows removed** 
- Remove Outliers
- Fix inconsistences **Multiple Speeling and formatting changes**
***

## **Analysis** 
Before you start conducting in-depth analysis, it’s important to first get acquainted with your dataset—to get the “lay of the land,” if you will. This is where exploratory data analysis comes in.

### Descriptive statistics 

Calculating a basic table for Mean, Median,Min and Max on Trip Duration and User age. As we can see the maximum in trip duration has an outlier. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Stat.png" >

Top 20 pick-up locations, sorted by the data by count, in descending orderusing a pivot table. This chart gives us the top 3 spots, Grove St Path, Exchange Placeand Sip ave. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Count.png" >

Explore how the average trip duration varies across different age groups again using a pivot table. In review the 75+ age group has the highest duration, but that might be scewed to and needs further analysis. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Dur.png" >

Based on one of the pivot tables we created previously(average trip duration per age group), you might jump to the conclusion that the 75+ age group makes up the biggest segment of our NY Citi Bike customer base. Which age group rents the most bikes? 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Most.png" >

How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week? 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Sub.png" >

With the use of pivot tables we can quickly find the ansers to the business questions.

**Key Finding:** Grove St Path is the most popular pick up place.

**Key Finding:** 75+ age group took the longest trips.

**Key Finding:**  35-44 year old rent the most bikes

**Key Finding:**  Most NY Citi Bike users are long-term subscribers. 
***
## **Data Visualization**

Data visualization (or data viz) is all about presenting data in a visual format—such as a graph, chart, or map.

To show some visual charts to make the data stand out in a easy to see format. Here a horizontal bar chart was selected to easly show the difference between the top pick-up station. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Graph%20top%20.png" >

We already summarized the relevant data with a pivot table, in presenting as a visual it is easy to see that 75+ has the longest duration. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Graph%20Dur.png" >

 Created another bar chart, this time with the count of bikes rented per age group. It is easy to see that the 35-44 group is the most dominate group. 

 <image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Graph%20Num.png" >

 Here is a Double chart that highlights the differnce between people who rented the bikes. There is data in the table for one time users , it is hard to see. 

 <image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Graph%20Rent.png" >

Does user age impact the average bike trip duration? As already mentioned, we’ll be looking at the relationship between different variables. I will create a scatter plot, plotting trip duration vs age. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Gaph%20Scat.png" >

With the use of pivot tables we can quickly find the ansers to the business questions.

**Key Finding:** Scatter Plot dos not show any notable correlation between users age and how long they ride for. 
***

## **StoryTelling **

As a data analyst, your goal is to make data meaningful. You take raw data, analyze it, and draw out insights that can have a real-world impact. When you uncover these insights, it’s your job to communicate them in a way that means something. You need others to not only understand your findings, but to care about and act upon them. You do this by building a narrative or a story around your data 📚


### [Final Presention Slides](https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/NY%20Citi%20Bike%20Analysis.pdf)

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Storry%20Telling.png" >
