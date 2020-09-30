# PM2.5_of_US_counties

## Data

The data I propose to visualize for my project is from [Two Decades of Pollution in US](https://github.com/maurosc3ner/uspm25_2000_2018/blob/master/data/pm2.5byCounty.csv)

## Prototypes

I’ve created a proof of concept visualization of this data. It's a US map with counties and it shows the concentration of each county by the shade of color in a specific year. 

[![image](https://user-images.githubusercontent.com/18320430/94645772-b0e67d00-02ba-11eb-8fc4-4d205e878e1b.jpg)](https://vizhub.com/georgeeeee/39e845953d7547e5b2b8aede08714d87?edit=files&file=index.js)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which areas of US has the relatively high concentration of PM2.5 in each year? What about the areas with low concentration?
 * What are the tendencies of PM2.5 in each county US over time?
 * What is the highest historical PM2.5 concentrations for each county?

## Sketches

![image](https://user-images.githubusercontent.com/18320430/94642072-20576f00-02b1-11eb-8f19-58447ba7f63a.PNG)
The data of concentration of PM2.5 is presented by the shade of color of each county. The deeper the color refers to the higher PM2.5 concentration in that area. And there is a scrollbar on the bottom of the map which can be dragged by users to switch the year. The scrollbar will shift automatically after the initialization of the website to present the changes of PM2.5 over year. 

## Open Questions

So far I'm not sure how to realize the animation by d3 as well as how to load a portion of data in a single tiem frame because the data source contains all of the 18 years of the PM2.5 concentration value which needs to be presented year by year.
