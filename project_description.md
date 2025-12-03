# Visualizing life expectancy and fertility

## Research Question
The main research question:
How did life expectancy and fertility change between 1964 - 2013 for different countries and continents?

Additional research questions:
1.Did differences between countries become smaller or larger between years?
2.Which regions developed most in this time period?
3.Are there countries that experienced a decrease in life expectancy at some point in time? Can you explain why this happened?
Data source

## data
**Dataset** : gapminder.csv
**Source**: Gapminder.org
**Time period** : 1964-2013
**countries** : 244 
**Variable** :
Year
Country
Region
lifeExp
Fertility
Population (pop)

## Data characteristics
Time series data (50 years)
Spanning all regions around the world
Includes socio-economic indicators

## Visualization methods
The relationship between fertility rate and life expectancy is presented using an interactive scatter plot:
X-axis: Fertility rate (the average number of children born to each woman)
Y-axis: Life Expectancy (years)
Point size: The population size of a country
Point color: Region (continent)

## Interactive functions
1. **Time Slider** : Allows users to select specific years (1964-2013)
2. **Hover Tool Tip** : Displays detailed information of specific countries
3. **Legend Interaction** : Clicking on the legend can hide or show data of a specific region
4. **Dynamic Update** : Data is updated in real time as selected by year

## Tools
Python 3, pandas, Bokeh, Jupyter Notebook

## Steps

1. **Data Preparation**
Read and clean Gapminder data
Scale population data for visualizing point size
Classify and assign colors by region

2. **Visualization Design**
Create a basic scatter plot
Add axis labels and titles
Achieve color coding by region
Add legends and interactive features

3. **Interactive Functions**
Integrated time slider control
Implement real-time data updates for JavaScript callback functions
Add a hover tool tip
Set the interaction behavior of the legend

4. **Output**
Generate interactive charts in HTML file
Integrate into Jupyter Notebook


## Expected outcomes

### Main findings
It can be observed through visualization that:
1. **Global Trend** : Fertility rate declining, life expectancy rising
2. **Regional differences** : High-income regions such as Europe and North America entered the stage of low fertility rates and high life expectancy earlier
Europe and North America: Early transition to low fertility, high life expectancy
Asia and Latin America: Rapid development
Africa: Slower changes in some areas
3. **Exceptions**: Countries with life expectancy decreases in specific periods


## Limitations

### Data limitations
Data from some countries may be missing
The population data is an estimate
It cannot reflect regional differences within the country

### Technical limitations
The browser performance limit is to display 244 countries simultaneously
Simplified complex population dynamics
Static point size scaling may be misleading

## Future improvements
1. Add country search and filtering functions
2. Implement the playback of animation timelines
3. Integrated map view
4. Add a statistical summary panel
5. Support data download and sharing


Project development time: December 2023
* Developer: [Rongman Sun]*
