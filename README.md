# White House Budget Donut Visualisation
A donut visualisation of White House Budget. This project was initally started at [Gov Tech Hack](http://www.eventbrite.com/e/gov-tech-hack-by-the-people-for-the-people-tickets-16135863803).

Interesting note: how to visualize negative values in a pie chart? As an alternative, use a modified donut chart with each segment having the same width, but the height be depend on the value. Positive pushed the border outward, negative pushed the border inwards.

Use: D3.js


##Next Steps:
* Create animation where heights of the bars change how the budget has evolved over the years
* Add input to change the years temporarily
* Find the best way to use a sunburst chart with the way the data is currently structured? Consider going that direction
* Or when click on a portion, it expands into more options, shifting the entire pie chart

###Todo:
* Find a better way to unite the budget and refData array, and how they access it each other, etc
* use canvas instead of svg entirely?
* Move canvas comparison circles to the front rather than the rear...How to impliment??
* Too much canvas? Doesn't exactly look great when zoomed upon....Is that a concern or does it not matter?
* Have a button to toggle show all (even agencies with 0 overall spending)


###Curiosities
* For example try to use circles?
* Compare performance of dashed canvas comparison lines and svg based ones


* draw canvas ontop of svg -> set z-scores + fix positions