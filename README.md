Objective of the visualization:

This project aims to provide a narrative around how urbanization across the globe in different countries is driving GDP  and mobilizing the population to certain big cities.
As a result of this the cities are getting bigger and bigger in area with each passing day and finally resulting in depletion of forest area.This trend might prove harmful 
by severly damaging the environment with less forests and incresed pollution in certain  parts of the country.

Narrative Structure:
 
This visualization follows the structure of an Interactive Slideshow giving the viewer capacity to navigate through different slides and the details if needed 
and understand the impact of urbanization on different aspects like GDP,Population and deforestation.

Visual Structure:

The visual structure is based on scenes .Each scene is depicted using similar kind of layout and same template for visual consistency.
The title for each scene is placed above the visualization and helps in setting up the context for visualization.
The visualization container which displays the data and is consistent with height 510px, width 980px, and background color "grey" for each scene of the narrative visualization.
the graph varies as per the requirement of the scene to convey the narrative of the data in a proper way.
The scenes were designed for consistency to keep the viewer from getting disoriented through transitions.
the order of the scenes are placed in a story telling structure.


Scenes:

There are 4 web pages along with 4  scenes .
First page gives the context of overall project along with a scatterplot for urban area % vs gdp for various countries of the world.
There is nevigation in the form of web url's available from each page.The first page leads to 3 more pages(scenes) based on different types visualization providing detailed coverage on 
below topics.Please find below the navigation details:-
Page 1.GDP vs urban area coverage. It can lead to Page 2 and Page 3 for more information on data.It can also lead to Page 4 for final conclusion.
Page 2.country wise urban area. It can lead to page 1 (back) and page 4 (Next)
Page 3.trend of increasing population in urban area across different countries. This can lead to start (Page1) or final Page (page 4)
4.Depletion of forest cover across different countries over range of years. This is the final Page. It can lead to start as well as back to page 3.
The final conclusive page provides the result of data visualization.Also It can lead to About this visualization Page on github.

Annotations:

Annotations are used to highlight a trend in the data, direct the user to further investigate the data, and ask the user to draw a conclusion from the data. The annotations use a consistent template for font size and a bolded style.

The annotation in page 1 (scatterplot -gdp vs urban area) is text positioned inside the visualization container meant to highlight the primary finding of the visualization. "As Urban area increases GDP increases across most of the countries." When the user clicks the hyperlink of (Next Page) to transition forward to 2nd page which contains(2nd scene) the annotation for 1st page is no more visible.
The annotation in page 2 (urban land % vs countries) is text positioned inside the visualization container meant to highlight("Most developed countries have higher urban Area"). The user is invited to mouseover the data to see the trends for Cars, Trucks or SUVs independently. When the user clicks the button to navigate away to Scene 1 or forward to Scene 3 the annotation for Scene 2 is cleared.
The annotation in page 3 (urban population increase % vs countries) is text positioned inside the visualization container meant to highlight "Urban area population tend to increase with time". When the user clicks the button to navigate back to Scene 1 or to Scene 2 the annotation for Scene 3 is cleared.
The final page 4 (increase in deforestation(%) vs countries) annotation shows "As urbanisation increases ,deforestation increases".
Also in each page or scene there are annotations in the form of tool tips which comes with mouse hover.

Parameters:

Parameters are used to engage the user in the narrative visualization and further explore the data. The parameter used in this visualization are the embedded url's to navigate the slides .
once clicked on the embedded slides it takes the user to another scene or slide .Also When mousing over a data point belonging to a particular country, the pop up comes with data points related 
to that country and visualization which is kind of change in visualization. This allows the user to gain more information about the actual values below the visualization.this forms another set of parameter.


Triggers:

Triggers are utilized in two ways for this visualization.
one is to navigate from one scene to another scene through "mouse clicks" over the embedded web links.
And the other way they are used is to show up the pop ups whenever there is "mouse hover" over the bars in bar chat or over the circles in scatterplot.


