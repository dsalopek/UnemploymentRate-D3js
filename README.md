# Unemployment Rates
## An Interactive Unemployment Rate Data Visualization Web Application 
[![](https://img.youtube.com/vi/X1pHHATD8mw/0.jpg)](https://www.youtube.com/watch?v=X1pHHATD8mw)<br/>
[Link to application page](https://dsalopek.github.io/UnemploymentRate-D3js/)
### Overview
This is a web application written in D3js to visualize the unemployment rates for all 50 states. Data was obtained from the BLS website. Dates for data range from 1978 to 2016.
The focus chart is the topmost element, with the appropriate title and axis labels. The middle element is the time interval selector, as well as a contextual representation of the entire data set.<br/>
### Using the application
You can compare unemployment data from different states by selecting the state from the map underneath the graphs. You can also choose to include the national unemployment data if desired. You can do this by selecting the bottom left button, labelled 'Include National Rate'. When hovering over the data line in the focus graph, the line will bold as well as bring up a tooltip with the selected state's name. If there are other data lines in the grpah, they will fade, as well as any states in the map that are not the selected state. You can zoom in to a time interval by clicking and dragging the cursor in the contextual graph (the middle one). Clicking the button labelled 'Clear All' will clear the data from the graphs and map. If you would like to view all 50 states and national rates at once, click the button labelled "Include All 50 States".<br/>
### Notable Data Characteristics
After implementing the application features and plotting the data, I noticed a few characteristics of the data. I have highlighted them in the image below.<br/>
##### West Virginia 1980-1985
A massive jump to over 20% unemployment. This is the highest unemployment rate of any state since 1978. This can be attributed to the Early 1980's Recession.<sup>1</sup>
##### Louisiana Early 2005
A sharp increase and decrease in early 2005 attributed directly to the natural disaster, Hurricane Katrina.<sup>2</sup>
##### National Rate 2010
A national increase of unemployment, this is attributed to the recession that started in 2008.<sup>3</sup> Michigan had the highest unemployment rate in this time. Perhaps it was due to the bailout of the automakers in Detroit.<sup>4</sup><br/>
![Imgur](http://i.imgur.com/eBBsjge.png)<br/>

### Notes
This application was adapted from various examples from the creator of D3.js, Mike Bostock. This application was written for a project in CS4331 at TTU, Data Visualization and Visual Analytics.<br/>
*Note that this application does not run correctly on Safari browser.*
##### References
<sup>1</sup>Congressional Budget Office, "The Prospects for Economic Recovery", February 1982. "The downturn was precipitated by a rise in interest rates to levels that exceeded the record rates recorded a year earlier" (p. xi)
<br/><sup>2</sup>Bureau of Labor Statistics,. The Effect Of Hurricane Katrina On Employment And Unemployment. Bureau of Labor Statistics, 2006. Print.
<br/><sup>3</sup>Bureau of Labor Statistics,. Unemployment Remains High In 2010. Bureau of Labor Statistics, 2011. Print.
<br/><sup>4</sup>Gable, Mary and Douglas Hall. "Ongoing Joblessness In Michigan". Economic Policy Institute. N.p., 2013. Web. 4 Oct. 2016.
