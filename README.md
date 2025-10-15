# Google Case Study: 

perform data analysis for a fictional bike-share company in order to help them attract more riders

# Business Problem
 - Converting casual riders into annual members 

Data source:
    - 12 csv files of approx. 2-3 millions rows of data  

# Testing sample data before working on the full datasets on Excel to understand what im working with

Data cleaning: 

1) Removing duplicates  
2) Removing unnecessary columns since they won't be helpful  

    rideable_type ,start_lat start_lng ,end_lat,end_lg 

3) Reformating start_at and end_at columns for better readability  

4) Create start_at_date and start_at_time columns 

5) Create end_at_date and end_at_time columns  

6) Delete the start_at and end_at columns 

7) Checking for blank cells and highlighting it with conditional formatting  
    - will check back on it during the final steps 

8) Create ride_length column 

9) Create weekday column 

10) Return to blank cells  
    - end_station_name and end_station_id has several blank cells  
    - Remove it from the data, 99 records deleted 

11) bad data on the ride_length  
    - notice #### which indicate negative number  
    - notice some values are less then 1 mins which will not useful for my analysis  
    - Remove it and 388 records are deleted   




