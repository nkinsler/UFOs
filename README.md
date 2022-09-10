# UFO Sightings

## Overview of the Analysis

The purpose of this analysis is to create a webpage with a dynamic table that allows users to filter for multiple criteria at the same time.  The additional filters to be created are: city, state, country, and shape.

## Results

[UFO Sightings](https://github.com/nkinsler/UFOs/blob/main/index.html)

[App](https://github.com/nkinsler/UFOs/blob/main/static/js/app.js)

Header page is setup as discussed in the Module.

![Header](https://github.com/nkinsler/UFOs/blob/main/static/images/Truth.png)!

Filters created for date, city, state, country, and shape.  Each of the filters have a placeholder for the filter that does not impact the search the user may perform.

![Starting](https://github.com/nkinsler/UFOs/blob/main/static/images/Start.png)!

To filter by date, the user would enter the month (1-12), the date (1-31), and the year (4 digit year).

![Date](https://github.com/nkinsler/UFOs/blob/main/static/images/Date.png)!

To filter by city, the user would enter the city in all lowercase.

![City](https://github.com/nkinsler/UFOs/blob/main/static/images/City.png)!

To filter by city, the user would enter the state in all lowercase using their two letter abbreviation.

![State](https://github.com/nkinsler/UFOs/blob/main/static/images/State.png)!

To filter by city, the user would enter the country in all lowercase using their two letter abbreviation.

![Country](https://github.com/nkinsler/UFOs/blob/main/static/images/Country.png)!

To filter by city, the user would enter the shape in all lowercase.

![Shape](https://github.com/nkinsler/UFOs/blob/main/static/images/Shape.png)!

The user could even enter multiple filters to narrow their search even further.

![Multiple](https://github.com/nkinsler/UFOs/blob/main/static/images/Multiple.png)!

## Summary

There are two major drawbacks of this webpage:
1. The user must user certain parameters in order to search.  As mentioned above, the user had to use all lowercase in order to perform the search.  In addition, the user also had to use the two-letter abbreviation for states and country.
2. The data file provided was limited to a short period of time not providing as many searchable results the user may want.

## Recommendations

1. Modify the search bar as follows:
    - Have a calendar appear for the date filter allowing the user to select a date.
    - Have a list of available cities, states, countries, and shapes appear as a drop down in the search bar.
    - Provide the user the option to either select (as mentioned above) or type in their search.
2. Modify the webpage to allow the use of lowercase, uppercase, or mix in order to perform the search.
3. Add a filter to pick-up key words in the comments.
