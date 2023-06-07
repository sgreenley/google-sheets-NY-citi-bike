# Google-Sheets-NY-citi-bike 🚴

**Background** 

 Citi Bike is the largest bike-share program in the United States, with 20,000 bikes and over 1,300 pick-up stations across Manhattan, Brooklyn, Queens, the Bronx, and Jersey City. As stated on their website, the service was designed for quick trips with convenience in mind, offering a fun and affordable way to get around town. Users can sign up for annual membership, or buy a short-term pass through the Citi Bike app. Once they’ve joined, they simply locate a nearby bike, ride around as they please, and return it to a nearby station once they’re done 

### [Final Presention Slides]()


**Assigment**

Your mission is to analyze data collected by Citi Bike and help key stakeholders to make smart, data-driven decisions based on the insights you uncover. Here’s what you’ll seek to investigate:

 1. What are the most popular pick-up locations across the city for NY Citi Bike rental?
 2. How does the average trip duration vary across different age groups?
 3. Which age group rents the most bikes?
 4. How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week?
 5. Does user age impact the average bike trip duration?

## **Data Cleaning** 

Here is a visual of the source data set before cleaning 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Ny%20unclean.png" >

We’ve established how important the data cleaning stage is. To clean the data, I completed the following: 
- Delete unnecessary columns 
- Remove duplicates **3555 rows removed** 
- Deal with missing data **3 rows removed** 
- Remove Outliers
- Fix inconsistences **Multiple Speeling and formatting changes**


## **Analysis** 
Before you start conducting in-depth analysis, it’s important to first get acquainted with your dataset—to get the “lay of the land,” if you will. This is where exploratory data analysis comes in.

### Descriptive statistics 

Calculating a basic table for Mean, Median,Min and Max on Trip Duration and User age. 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Stat.png" >

Top 20 pick-up locations, sorted by the data by count, in descending order.

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Count.png" >

Explore how the average trip duration varies across different age groups

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Dur.png" >

Based on one of the pivot tables we created previously(average trip duration per age group), you might jump to the conclusion that the 75+ age group makes up the biggest segment of our NY Citi Bike customer base. Which age group rents the most bikes? 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Most.png" >

How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week? 

<image src="https://github.com/sgreenley/google-sheets-NY-citi-bike/blob/main/assets/Desc%20Sub.png" >

## **Data Visualization**
