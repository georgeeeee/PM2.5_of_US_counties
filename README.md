# PM2.5 of US counties
The final version of the [Data Visualization final project](https://github.com/georgeeeee/PM2.5_of_US_counties).

## Data
The data I propose to visualize in my project is from [Two Decades of Pollution in US](https://github.com/maurosc3ner/uspm25_2000_2018/blob/master/data/pm2.5byCounty.csv).

## Sketches
The data of concentration of PM2.5 is presented by the shade of color of each county in the US. The deeper the color refers to the higher PM2.5 concentration in that area. And there is a slider on the bottom of the map enabling users to switch the year they want. The slider will shift automatically after the initialization of the website to present the changes of PM2.5 concentration over year. 

![image](https://user-images.githubusercontent.com/18320430/94642072-20576f00-02b1-11eb-8f19-58447ba7f63a.PNG)

## Prototypes
This rough prototype is implemented by VegaLite API without adding the slider on the bottom. Besides the cholopleth map of Alaska and Hawaii are not actually shown as they are transparent. The final deliverable will be finished by using React & D3.
Inspired by [Choropleth](https://observablehq.com/@d3/choropleth).

[![image](https://user-images.githubusercontent.com/18320430/94645772-b0e67d00-02ba-11eb-8fc4-4d205e878e1b.jpg)](https://vizhub.com/georgeeeee/39e845953d7547e5b2b8aede08714d87?edit=files&file=index.js)

## Questions & Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which areas of US has the relatively high concentration of PM2.5 in each year? What about the areas with the relatively low concentration?
 * What are the tendencies of PM2.5 in each county US over time?
 * Is there a correlation between the year and the PM2.5 concentration?

## Open Questions
So far I'm not sure how to realize the animation by d3 as well as how to load a portion of data in a single time frame because the data source contains all of the 18 years of the PM2.5 concentration value which needs to be presented year by year.

## Schedule of Deliverables
task | estimated delivery week
---- | ---
deal with the "NA"s in the csv file | before week 7
draw the wireframe of the USA with county | before week 7
fill the wireframe by colors based on a single year of concentration data | before week 8
enable zoom in & zoom out | before week 8
add a slider at the bottom of the map | before week 8
show the concentration of a random year between 2000 and 2018 | before week 9
show the tooltips of each county's concentration | before week 9
enable the changes of the concentration by sliding from 2000 to 2018 | before week 9
finish the final project proposal | before week 10
finish the portfolio video | before week 10

*The end of each week is assumed on Wednesday.*

## Final Deliverable
The final deliverable is completed mainly based on the sketches and prototype except for some minor changes such as shifting the position of the color legend and the slider, reversing the color legend, and so on. Besides, the slider will start to shift only after clicking the 'play' button instead of shifting once the webpage is initialized.

[![image](https://user-images.githubusercontent.com/18320430/98187134-3a065a80-1ede-11eb-9c4b-19fe10b8ebd2.jpg)](https://vizhub.com/georgeeeee/6f114e2add8f4dc49d1e1e9624febcb0)

## Timeline
Finished by 10/14
- [x] Filled the area with no data record by grey color.
- [x] Drew a wireframe of the US map with counties.
- [x] Filled the wireframe by the PM2.5 concentration data in 2000.

Finished by 10/21
- [x] Added a slider to let users choose the year of concentration (the change of value after sliding is yet to be done). 
- [x] Added a color legend to show a correlation between color and value of concentration.

Finished by 10/28
- [x] Finished the year slider.
- [x] Added transitive animation on color while switching year.
- [x] Added tooltips to show the county, state, and the value of concentration while hovering on each county.

Finished by 11/04
- [x] Added the mesh of the states.
- [x] Added four ticks on the color legend to show the quantile of the concentration.
- [x] Added a play button to enable slider to switch the year all way down to 2018 automatically.
- [x] Highlighted the county border while hovering.

## Future Work
- Assmble zoom in/zoom out
- Performance optimization
