# UFOs
Module11 JavaScript

Link to deployed UFO webpage can be found here: 

https://cthompsonlbi.github.io/UFOs/

## Overview of Project:
The overview of this project is to take a website that accepts a single input field to filter data and expand it to allow the user to filter UFO sighting data using multiple critieria's.  Instead of having just the option to search for UFO sightings based on date, we will be adding the ability to search for UFO sightings based on date, city, state, country, and/or shape.  We will achieve this by using JavaScript, CSS and HTML.
### Purpose:
The purpose of this project is to assist Dana in allowing users to sort through the available data by searching on multiple parameters so that the user can review the UFO sighting data and decie for themselves what may be real UFO sightings and what may be a government conspiracy.  Walking Dana through the webpage with the new upgrades that allow be better search flexibility by allow to filter using multiple parameters, she will see the following upon loading the webpage:

* By modifying the Index HTML file as shown below, we can set the webpage up to handle 5 inputs:

![index_html_5fields](resources/index_html_5fields.png)

* When loaded, the user will see five input fields to help them search for specific UFO sightings.

![filterSearch](resources/filterSearch.png)

* The table will be built using the function created below:

![buildTableFunc](resources/buildTableFunc.png)

* The table will be fully populated upon the loading of the webpage

![InitialTablePop](resources/InitialTablePop.png)


![filterTableFunc](resources/filterTableFunc.png)


![pslFilter](resources/pslFilter.png)
![tableFIlterPSL](resources/tableFIlterPSL.png)


## Results:
## Summary:
This was an interesting project and learned a lot.  One of the drawbacks that I saw from a user perspective is there is nothing in place to notify whether or not a parameter like, date, city, or country that is entered is valid.  To address this there are a couple of approaches that could be implemented.  The first being error messaging.  If an user inputs and invalid date, city, country or shape or the input does not exist, a message should return stating that the "Input entered by the user does not exist, please modify your input and try again".  A second option is to offer to return data based on a date range, or a radius.  If the user of the website did not put in a location that is present in the list of available data, it could return filtered data based on dates plus or minus seven days or if a city that is inputed by the user does not return an exact match then a radius option can be selected to return locations within the selected radius.
