# Excel-Projects


[Bike Sales Project](https://github.com/jmamasig/Excel-Projects/blob/main/Bike%20Sales%20-%20Excel%20Project.xlsx)


In this project we are given a set of customer data from a franchise bike shop. The end goal of the data should be to identify the who the target audience is in terms of likeliness of purchasing product. The finidngs can then be used to brainstorm ideas of how the customers who have not purchased product previously can be converted into the group that has purchased product. Below is the raw data collected that we start with.
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/b44c5b8d-e370-4e6e-b392-b73af285a056)


First step in cleaning and organizing the data is removing any duplicates from the table. Removing duplicates is done through Excel's "Remove Duplicates" tool. Since each customer is given a unique ID, and this data does not account for multiple visits within the store, there should be no duplicate customers in the data. The next step we take is to make the data more readable. There is a discrepancy in regard to single letters being used to identify a customer's Marital Status and the customer's Sex. To make this easier to read we use Excel's "Find and Replace" tool to list the data as "Marraige" and "Single" for Marital Status, then "Male" and "Female" for Sex. We do a small touch up on the Currency column by reducing the amount of decibles and a small touch up on the Commute Disatance column by changing "10+ Miles" to "More than 10 Miles" for ease of use with our functions. Then for the ages we categorize each age into an age bracket that we place in the new column, Age Brackets. The quickest way to do this without manually going row by row is to use a nested IF statement in Excel's functions. The nested IF statement used can be viewed below.
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/f7c8b9ee-8382-4eff-a1f7-58169778c017)


After all those steps have been completed we are left with a much more organized set of data.


![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/a8e31318-3fcf-47e2-bb5c-c32147f0d372)


Now we move on to creating assets for our dashboard. We start by creating several pivot tables that are valuable to the company ultimately to answer the question of, "Which customer's have purchased a bike?" Deriving from this question we are met with four pivot tables that answer this question:


  1. The average income of customers
  2. The customer's commute distance
  3. The customer age brackets
  4. The customer's occupations
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/887c2c7f-b80f-4fb4-af64-3cccf872d953)
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/515099b2-1e4c-41b0-b2c9-8a0042e10e6c)


Each pivot table showcases the customers who purchased bikes after their visit and customers who did not purchase a bike after their visit.


With these pivot tables created we can now move on to creating our dashboard. We import each pivot table on to a new sheet and organize it to how we see fit. Then to make the dashboard interactive and allow viewers to filter by other key aspects we can implement slicers using Excel's "Insert Slicer" tool. This will allow people to filter key aspects like the customers number of children, the number of vehicles they own, their marital status, and their native region. These aspects further identify which group of customers are not purchasing products after their visit. After some organization and creative direction the dashboard is completed and can be used by any viewer to filter for the specific aspects they are searching for.
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/5cd91a77-20b1-4047-8aac-01f95867d625)


One statistic result that is apparent is customers are more likely to purchase a bike if they have more available income seen here. The company can then use this information to think of new ways to target people with lower income to purchase a bike. Another aspect that can be highlighted is customers in the Pacific region are more likely to purchase a bike than North America or Europe. With this information the company can do further market research to find out why this is the case.
![image](https://github.com/jmamasig/Excel-Projects/assets/123910790/c2ffe38f-7387-419b-8a00-046b5dbad1a8)
This is just the surface and a rough idea of how the information can now be utilized by the company. The combination of filters can be used to find and pinpoit exactly which group of customers the company wants to target. 
