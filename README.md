# UFO Challenge Analysis

## Overview of Project

1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
2. Describe JavaScript syntax and ideal use cases.
3. Build and deploy JavaScript functions, including built-in functions.
4. Convert JavaScript functions to arrow functions.
5. Build and deploy forEach (JavaScript for loop).
6. Create, populate, and dynamically filter a table using JavaScript and HTML

## Resources
Data source: Challege Starter Code, data.js
Software: VSCode, GitBash

## Purpose
Dana wants to create a searchable database for users to be able to looke up UFO sightings. The webpage will deature a table that displays the data which has previously been stored in a JavaScript array. This challenge consists of building on a date filter to allow users to filter for multiple criteria at the same time. Users will be able to filter by date, city, state, country, and shape of sighting. 


## Results
The UFO Website was edited to contain multiple filters for finding UFO sighting information. The homepage now includes filters for data, location, and shape. The updates allow one to search by shape or location, or even multiple filters. 

![UFO Website - Pre-Filter](https://user-images.githubusercontent.com/88064181/137225487-b4227012-a109-43c7-b535-62c53ea3d3d9.png)

![UFO Website - nj filter](https://user-images.githubusercontent.com/88064181/137225491-47d54133-9407-410e-acd6-cb0b7e5c1879.png)

![UFO Website - Date](https://user-images.githubusercontent.com/88064181/137225496-0fa71a3d-34ef-49d7-bd5e-b162ea182dd6.png)


## Summary 

While the website is looking great thanks to Bootstrap and CSS components, there are some drawbacks that keep it from being fully functional. Users of this website must know the exact location they are searching for, and type it into the filter as it was typed in data.js. If the user capatalizes a letter that is not capital in the data, the filter will not recognize the location. As seen below, a user searched for "NJ" instead of "nj" and was returned zero results. Furthermore, the filter only allows a user to search for a singular date. Again, if the user is off by one day, it will not come back with any data for the user. 


![UFO Website - NJ error](https://user-images.githubusercontent.com/88064181/137225506-9a962e7d-f250-4e96-848f-235de4fbae26.png)

These drawbacks are easy enough are easy enough to fix to allow for a more user-friendly filtered data table. An update to the city and state filters to allow for additional spaces and accept upper/lower case letters will allow users to see the city/state they are asking for as long as it is spelled correctly. 

Furthermore, an additonal filter can be added for the location to allow the search to pull up nearby cities based on mileage. Perhaps a user is searching their hometown, which does not have a UFO sighting. If the user sets the distance filter, they can bring up UFO sightings within 10, 25, 50, or 100 miles of their house. 

Finally, to expand on the date filter, instead of filtering for a singular date, the filter should be updated to allow users to filter for a date range. This helps to accommadate for user error in case they don't know the exact date for the UFO sighting they want to look up.   
