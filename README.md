# UFOs with JavaScript

## Overview of Project
In this module, we built a table using data stored in a JavaScript array. We also created filters to make this table fully dynamic.  It reacts to user input, and then places the table into an HTML file for easy viewing.  We customized our webpage using Bootstrap, and equipped our table with several fully functional filters that allow users to interact with the visualization.

![layout](https://user-images.githubusercontent.com/88443672/141168360-884e9f9b-3667-4bb3-8601-6d6e5c5c688c.png)


## Code to Filter
First we created a event to listen for changes to the input fields.  If the input field was changed, the updateFilters function updates the filters list to reflect the user entry.

![eventlistener](https://user-images.githubusercontent.com/88443672/141170380-f75b6aed-0bc4-4cf8-a6a0-79466acc8a58.png)

![updateFilters](https://user-images.githubusercontent.com/88443672/141170393-8183aa10-e952-42db-9081-914f79cc5fbc.png)

After creating a functino to update our filters list, we creeated a function to loop through the data and keep the data applicable to the filters entered by the user.

![filtertable](https://user-images.githubusercontent.com/88443672/141170496-13620d0a-9347-47ee-8cde-b7c7d438793d.png)

## Result
After implimenting the above code, the result allows us to filter the JavaScript array based on multiple criteria.  Please see the examples below.

Filtering the JavaScript array for the city "El Cajon"

![filterforcity](https://user-images.githubusercontent.com/88443672/141168660-4d5c8052-6160-4104-bf5f-de2d2673ffff.png)

Filtering the JavaScript array for the city "El Cajon" and date "1/4/2010"

![cityanddate](https://user-images.githubusercontent.com/88443672/141168671-7c9303bb-a469-43ba-b57b-d17c0f730c2c.png)

Filtering the JavaScript array for the city "El Cajon" and shape "light"

![cityandshape](https://user-images.githubusercontent.com/88443672/141168682-eaddad47-179f-4028-9bca-eade32c9c6b0.png)

## Summary

