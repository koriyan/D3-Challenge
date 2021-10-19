# D3-Challenge

![DataViz](https://www.ae.be/hs-fs/hubfs/Blog/datavisualizationtips_hdr.jpg?width=1314&height=736&name=datavisualizationtips_hdr.jpg)

## Background

This Data Journalism challenge aims to run a series of feature stories about the health risks facing particular demographics by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the challenge is based on ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/). The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Interactive Visualization

![animated-scatter](Images/D3_KY.mov)

#### 1. More Data, More Dynamics

Include different demographics and risk factors. Place additional labels in the scatter plot and give them click events so that the users can decide which data to display. Animate the transitions for the circles' locations as well as the range of the axes. 

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Add tooltips to the circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged).
