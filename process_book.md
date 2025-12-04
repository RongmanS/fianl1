# Project Learning Process Record

## Day 1: Basic Learning and Setup
**What I worked on**:
Created a GitHub repository for the project
Read Gapminder dataset (gapminder.csv).
Installed Python and necessary libraries (Bokeh, Pandas, NumPy, Jupyter).

**Problems I encountered**:
GitHub setup was confusing at first.
First time using Bokeh, not sure how to start interactive plots.
Some columns have large numbers, need scaling for visualization.

**What I learned**:
How to install Python libraries using pip.
Basic GitHub operations: create repository, add files, commit.
Need to normalize population for point size.

**Resources used**:
Instructions at course website.
Python pandas documentation.


## Day 2: Basic visualization
**What I worked on**:
Loaded the Gapminder data using Pandas.
Created a simple scatter plot with Matplotlib first.

**Problems I encountered**:
Data had missing values and special characters that caused errors.

**What I learned**:
Basic Bokeh plotting: figure(), scatter(), show().
The difference between static (Matplotlib) and interactive (Bokeh) plots.

**Resources used**:
Bokeh quickstart guide.
Online examples of scatter plots.


## Day 3: Visual encoding optimization
**What I worked on**:
Added color coding to show different continents.
Made point size represent population size.
Added a legend to explain the colors.

**Problems I encountered**:
Category10 palette did not have enough colors for all continents.
Population numbers were too big - some points were huge, some tiny.

**What I learned**:
How to scale population data for better visualization.
Different color palettes available in Bokeh.

**Resources used**:
Bokeh color palette documentation.
Mathematical scaling formulas.


## Day 4: Interactive tools
**What I worked on**:
Added hover tooltips to show country details.
Made tooltips show country name, year, life expectancy, fertility, and population.

**Problems I encountered**:
Too much information in tooltips made them messy.

**What I learned**:
How to configure HoverTool in Bokeh.
The importance of showing only necessary information.

**Resources used**:
Bokeh HoverTool documentation.


## Day 5: Time slider implementation
**What I worked on**:
Added a slider widget to select the year.
Created JavaScript callback function to update data when slider moves.
Made the plot title update with the selected year.

**Problems I encountered**:
JavaScript callback was very difficult to write.
Slider did not work properly at first.

**What I learned**:
How Bokeh JavaScript callbacks work.
How to connect Python data with JavaScript code.

**Resources used**:
Bokeh JavaScript callback examples.


## Day 6: Performance optimization
**What I worked on**:
Separated data into different sources for each continent.

**Problems I encountered**:
After the year changes and adiing the legend, the picture was blank or stay the same.

**What I learned**:
Each region needs to have a separate ColumnDataSource. Create your own ColumnDataSource for each region. 
The slider callback updates the data of each region. And the legend color and clickable hide function can be maintained, while the scattered points move when the year changes.

**Resources used**:
Bokeh performance optimization guide.

## Day 7: Layout and integration
**What I worked on**:
Tested the visualization.
Added a download button for the HTML file.

**Problems I encountered**:
File download did not work properly.

**What I learned**:
How to export Bokeh plots to HTML.

**Resources used**:
HTML export examples.

## Day 8: Documentation and refactoring
**What I worked on**:
Added comments to explain the code.
Created project documentation files.

**Problems I encountered**:
Documentation took more time than expected.

**What I learned**:
How to try to write helpful comments.

**Resources used**:
Code documentation examples.

## Day 9:
**What I worked on**:


**Problems I encountered**:


**What I learned**:


**Resources used**:


## Day 10:
**What I worked on**:


**Problems I encountered**:


**What I learned**:


**Resources used**:






