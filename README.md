# SQL-Project- Restaurant data analysis

I want to open a restaurant in New York City ...

Given data tables:
1. restaurant_data
2. violation_data 

	In this project we retrieved the given data tables from Azure to our Jupyter notebook. 
Then we saved the data in dataframes using SQL queries. For the rest of the project we will 
be using pandas dataframes to manipulate the data. 

	Our next step was combine both tables. That made our data larger since each restaurnat 
can have multiple violation. By doing that we also have a lot of null values. Next step is to 
clean the data for any null values. 

	We are analyzing the data by borough and grades. Our aim is to find the most 
popular borough and the most popular grade that shows the success of the restaurants. Since
Manhattan is the most popular borough with the highest "A" grade restaurants, our search 
will only be within Manhattan. Then we look for the violation grades in Manhattan. 
The majority of the violations grades are "A." To make our search even smaller, we will be 
looking at restaurants with "A" grades. 

	Our next goal is to find the most popular cuisines in Manhattan within the "A" grade
restaurants. Based on the search, "American" cuisine is the most popular and has the 
highest number of "A" grades. 

	Finally, to reduce the data even further, our next goal is to get the top 20 
zip codes with the highest number of restaurants with "A" grade and the most popular cuisine.
Since we have to worry about competitions in those zip codes for businesses, 
we figured or analyzed that any zip code with less than 400 restaurants is suitable for 
an American cuisine restaurant with less competition. This would create a successful 
restaurant.  


Our search is based on Manhattan > Grade > Popular Cuisine > Top 20 Popular Zip Codes