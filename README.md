# NYC/Des_Moines_Citi_Bike_Challenge
---
## Overview
The purpose of this exercise was to create a dynamic webpage with a table including mutliple search criteria for Dana and her data set of UFO activity. The initial webpage only included a date filter with an executable button.   To add further functionality the filter button was removed and we added filters for city, state, country, and shape.   Results mimic any and all filters applied to the dataset and return the updated results when "return" is hit.

## Analysis Results

### Top Starting Locations
![Screen Shot 2021-10-28 at 2 33 47 PM](https://user-images.githubusercontent.com/84201082/139316520-ca6d3343-3116-451a-9f5f-8cec94bba7d9.png)
Most popular starting locations are in the Manhatten/ downtown area and dissapate outside of that area.

### Top Ending Locations
![Screen Shot 2021-10-28 at 2 34 33 PM](https://user-images.githubusercontent.com/84201082/139316585-adb8368a-736c-4000-924f-23c932b44943.png)
Top End Locations mimic those of the Top Starting Locations within the Manhatten/ downtown NY area.

### Duration Times for All Users
![Screen Shot 2021-10-28 at 2 41 48 PM](https://user-images.githubusercontent.com/84201082/139316620-0f1cbd70-9b9d-4523-b44f-c3e5e857a115.png)
The majority of Bike Rentals are used for very short periods of time and fall between 1 and 24 mins with the most popular being the 5 min mark.

### Duration Times by Gender
![Screen Shot 2021-10-28 at 2 42 07 PM](https://user-images.githubusercontent.com/84201082/139316648-f9566f86-82e2-4fa1-af8d-51f3c4dea3d2.png)
Most Genders were able to be identified for this analysis.   The Male gender dominates in terms of both number of bike rentals as well as total minutes rented. No uselful information is gleaned outside of the 1 hour mark.

### Popularity of Bike Rentals by Day & Time for All Users
![Screen Shot 2021-10-28 at 2 42 38 PM](https://user-images.githubusercontent.com/84201082/139316678-c05e8e76-c917-45b4-9413-4bb4d6e212fd.png)
The most popular time for all users is during the morning rush from 6 AM-9AM and the evening rush between 5PM-8PM.   Monday, Tuesday, and Thursday see the most ammount of usage during the week.

### Popularity of Bike Rentals by Day & Time by Gender
![Screen Shot 2021-10-28 at 2 42 53 PM](https://user-images.githubusercontent.com/84201082/139316707-a8312d36-6560-450f-bd11-0cbe16632e61.png)
Between the Male and Female genders the results mimic the combined results in the prev. chart and are still dominated by the male category.

### Popularity of Bike Rentals by Day, Gender, and User Type
![Screen Shot 2021-10-28 at 2 43 17 PM](https://user-images.githubusercontent.com/84201082/139316728-7ddcd3aa-8606-40c5-8aee-bfd1ce0a57b9.png)
Subscribers of the service tend to be Male and usage is most heavy during the work week. Customers are fairly neutral across the board both in terms of gender but also days used.
___

## Summary
One drawback of the designed webpage is the search functioinality.  If you mispell or dont spell out completely your desired filter criteria your results will show blank. (Example Below)
![Screen Shot 2021-10-01 at 12 06 49 PM](https://user-images.githubusercontent.com/84201082/135652640-ee05ea8f-d45f-4fb3-b63e-4ae313f817c8.png)

Two recommendations for further development would be to add a fuzzzy search capability or spellcheck option for fields that must remain free text fields.   In addition to this I would also sugguest list dropdowns for categories for those filters without too many selections such as the Shape filter.   Also, despite an example of date format in the filter mistakess could still be made.   A pop out calendar where you can select the Year, Month, and date would help to avoid any issues.
