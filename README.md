# UFO Sightings with JavaScript

## Overview of Project
For this week's project, we will be using the coding language JavaScript. JavaScript is typically known as a front-end development language and has several uses specific to data visualizations. We will add JavaScript into an HTML page to display our data through a dynamic webpage. A dynamic webpage allows user inputs and updates based on the interactions. On our webpage, our main feature will be a table that will allow the users to refine their search through filters. CSS and Bootstrap will also be used to build and style the webpage.

### Purpose
The purpose of this week's project was to help Dana, a data journalist, post her UFO findings to a webpage. This dynamic webpage includes Dana's article and a table to display UFO sighting information such as date, city, country, shape, duration, and comments. The information used to populate the table was pulled from a JavaScript file. Because there was so much information, we also created filters to fine tune the results.

## Results

### Instructions
On our dynamic webpage, the users can search and filter the UFO sightings table based on date, city, state, country, and shape.

There is a "Filter Search" feature on the left-hand side of the page with the different search criteria.

Please notice in each input box, it displays an example, or a placeholder, for each filter option. For example, our placeholder for City is benton.
This will help show the user the input format for what they want to search on. 

![filtersearch](/Resources/filtersearch.PNG)

If nothing is entered in the Filter Search fields, by default the table will display all the UFO sighting information on the webpage.

![nofilter](/Resources/nofilter.PNG)

To start searching for specific UFO sightings, the user can enter date, city, state, country, and shape. Not all fields need to be populated in order for the table to update. The user can search on one field or multiple fields simply by entering what they want to search on and pressing "Enter".

##### Single Field Search
For this example, we will search for UFO sightings based on a specific date. The date we are using for this example is 1/13/2010. As you can see, the table on the righthand side is now only displaying UFO sightings for 1/13/2010. 

![datefilter](/Resources/datefilter.PNG)

##### Multiple Field Search
The user is also capable of searching on multiple fields. The example below is filtering on date (1/13/2010) and city (white oak). The table will then update to only show UFO sightings for 1/13/2010 in White Oak. 

![datecityfilter](/Resources/datecityfilter.PNG)

##### Additional Search Examples
Users can search UFO sightings based on state. Below is an example where we're searching on "nc" or North Carolina for state. The table will then update to only show results for UFO sightings in North Carolina. 

![statefilter](/Resources/statefilter.PNG)

Here is another example where we are searching on multiple fields. We entered "ca" or California for state, "us" for country, and "triangle" for shape. The table updates to only display the results based on what we input.

![multifilter](/Resources/multifilter.PNG)

## Summary

While our UFO sightings webpage is informational, visually appealing, and interactive, there are some drawbacks to what we have developed so far. One major drawback is that our search criteria fields are case sensitive. The user has to type in the fields exactly how they are displayed in the table or else the results will not populate. For example, states are displayed with all lowercase letters. If the user types in "NC" for North Carolina instead of "nc" in the State search field, no results will display since "NC" does not match "nc".

![ncstate](/Resources/ncstate.PNG)

### Recommendations
Here are two recommendations for further development:
- Add sorting options for columns of the table. This would be useful if the user wants to look at a specific state but wants to sort the cities in alphabetical order. 
- Have the option to search multiple user inputs in each search filter. For example, if the user wanted to look up a date range instead of a single date or have the option to view multiple states instead of a single state.