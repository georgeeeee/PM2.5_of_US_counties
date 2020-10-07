# PM2.5 of US counties

## Data

The data I propose to visualize in my project is from [Two Decades of Pollution in US](https://github.com/maurosc3ner/uspm25_2000_2018/blob/master/data/pm2.5byCounty.csv).

## Prototypes

I’ve created a proof of concept visualization of this data. It's a US map with counties and it shows the concentration of each county by the shade of color in a specific year. This portfolio is implemented by VegaLite. The final deliverable will be finished by using React & D3.

[![image](https://user-images.githubusercontent.com/18320430/94645772-b0e67d00-02ba-11eb-8fc4-4d205e878e1b.jpg)](https://vizhub.com/georgeeeee/39e845953d7547e5b2b8aede08714d87?edit=files&file=index.js)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which areas of US has the relatively high concentration of PM2.5 in each year? What about the areas with the relatively low concentration?
 * What are the tendencies of PM2.5 in each county US over time?
 * Is there a correlation between the year and the PM2.5 concentration?

## Sketches

![image](https://user-images.githubusercontent.com/18320430/94642072-20576f00-02b1-11eb-8f19-58447ba7f63a.PNG)
The data of concentration of PM2.5 is presented by the shade of color of each county. The deeper the color refers to the higher PM2.5 concentration in that area. And there is a scrollbar on the bottom of the map which can be dragged by users to switch the year. The scrollbar will shift automatically after the initialization of the website to present the changes of PM2.5 over year. 

## Open Questions

So far I'm not sure how to realize the animation by d3 as well as how to load a portion of data in a single time frame because the data source contains all of the 18 years of the PM2.5 concentration value which needs to be presented year by year.

## Schedule of Deliverables

task | estimated delivery week
---- | ---
deal with the "NA"s in the csv file | before week 7
draw the wireframe of the USA with county | before week 7
fill the wireframe by colors based on a single year of concentration data | before week 8
enable zoom in & zoom out | before week 8
add a scroll bar at the bottom of the map | before week 8
show the concentration of a random year between 2000 and 2018 | before week 9
show the tooltips of each county's concentration | before week 9
enable the animation of changes of the concentration from 2000 to 2018 | before week 9
finish the final project proposal | before week 10
finish the portfolio video | before week 10


*The end of each week is assumed on Wednesday.*


