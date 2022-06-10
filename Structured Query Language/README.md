# Structured Query Language Task

## Task Scenario

As a data analysis intern, you have to analyze sports data for a client. 
You are given two datasets related to IPL (Indian Premier League) cricket matches. 
One dataset contains ball-by-ball data and the other contains match-wise data. 
You have to import the datasets into an SQL database and perform the tasks given in this assignment to find important insights from this dataset.

About the Data:

The first CSV file is for ball-by-ball data and it has information of all the 193468 balls bowled between the years 2008 and 2020. 
It has 17 columns and below is the details of those 17

columns:

![image](https://user-images.githubusercontent.com/86974424/173030639-c3278f95-1806-41a2-b1bb-bacf528e19c0.png)

The second file contains match-wise data and has data of 816 IPL matches. This table has 17 columns and below is a short description of the columns in this table:

![image](https://user-images.githubusercontent.com/86974424/173030724-b82dc580-4067-4662-a536-803a3a01ffae.png)

Write queries for the following tasks:

1. Create a table named ‘matches’ with appropriate data types for columns

2. Create a table named ‘deliveries’ with appropriate data types for columns

3. Import data from CSV file ’IPL_matches.csv’ attached in resources to ‘matches’

4. Import data from CSV file ’IPL_Ball.csv’ attached in resources to ‘deliveries’

5. Select the top 20 rows of the matches table.

6. Select the top 20 rows of the deliveries table.

7. Fetch data of all the matches played on 2nd May 2013.

8. Fetch data of all the matches where the margin of victory is more than 100 runs.

9. Fetch data of all the matches where the final scores of both teams tied and order it in

descending order of the date.

10. Get the count of cities that have hosted an IPL match.

If you want to analyze data further you can write your own queries.

Datasets:

[IPL_Ball.csv](https://drive.google.com/file/d/1It3JnQPpNHCHoZyB6xLyTCP6prrzE3p-/view?usp=sharing)

[IPL_Matches](https://drive.google.com/file/d/18GFAORe6kWU6UQxNXSgoOofR9h8dZ7wU/view?usp=sharing)

##
## Solutions

### NOTE: For Detailed query output refer SQL Task Notebook also each and every task is queried which can be seen in the notebook and only output is shown here.

Task 1, 2: Create tables named ‘matches’ & 'deliveries' with appropriate data types for columns

![Capture](https://user-images.githubusercontent.com/86974424/173031856-9840f766-9a94-43b1-bca1-a4175f94cdbe.PNG)

Task 3, 4: Import data from CSV file ’IPL_matches.csv’ & ’IPL_Ball.csv’ attached in resources

![image](https://user-images.githubusercontent.com/86974424/173032214-eea84fdb-99b7-4ace-b85e-45acf56d3b79.png)
![image](https://user-images.githubusercontent.com/86974424/173032320-84f7e8ba-f0bb-461d-b1e7-5b9b8fc73a1e.png)

Task 5: Select the top 20 rows of the matches table.

![image](https://user-images.githubusercontent.com/86974424/173032449-f38c9c86-ed15-416b-be34-4c5ac178341e.png)

Task 6: Select the top 20 rows of the deliveries table.

![image](https://user-images.githubusercontent.com/86974424/173032639-11bfb6dc-a409-4c8d-b257-45a882508041.png)

Task 7: Fetch data of all the matches played on 2nd May 2013.

![image](https://user-images.githubusercontent.com/86974424/173032808-289885e8-9201-4ccf-bb4d-2fe53a221bde.png)

Task 8: Fetch data of all the matches where the margin of victory is more than 100 runs.

![image](https://user-images.githubusercontent.com/86974424/173032978-6558f859-bc2b-4dd2-aa65-2c3d6fca7302.png)

Task 9: Fetch data of all the matches where the final scores of both teams tied and order it in descending order of the date.

![image](https://user-images.githubusercontent.com/86974424/173033068-6c9a934c-71b5-46c8-ade0-b042a33a3d3a.png)

Task 10: Get the count of cities that have hosted an IPL match.

![image](https://user-images.githubusercontent.com/86974424/173033137-a07bf3e7-aff8-413d-8883-da2a915833a1.png)

Task 11: Name of cities that have hosted an IPL match.

![image](https://user-images.githubusercontent.com/86974424/173033254-8adda632-fc02-4555-817d-640f3c0f9656.png)

Task 12: Total No. of matches played in a city

![image](https://user-images.githubusercontent.com/86974424/173033333-2e0c1608-fde7-4c81-9db3-23b73c85d379.png)
