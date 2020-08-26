# Visualization-through-Geoplotlib
Interactive Data Analysis of AirBnB and Lyft Bikesharing through Python Visualization library

Developed by:
Swati Kohli, 
Poonam Patil, 
Sheel Kalburgi, 
Nikhit Soares, 

### Objective
This project is about exploring data through visualization using Geoplotlib (Python Visualization Library) features that is advantageous in communicating results related to geospatial analyses, for generating hypotheses during exploratory data analysis, supporting interactive data analysis and facilitating the iterative design for visualizations.

API refrences are available here: https://andrea-cuttone.github.io/geoplotlib/api.html

The dataset used for exploration is on AirBnB(San Francisco Bay Area), Lyft BikeSharing(San Francisco Bay Area) and Flights. The links can be found here:
 https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips
 https://www.lyft.com/bikes/bay-wheels/system-data

Geoplotlib is an open-source python toolbox for visualizing geo-graphical data. Geographical data visualization is a fundamental tool for communicating results related to geospatial analyses, and for generating hypotheses during exploratory data analysis.

### Features and Advantages
It provides implementations of dot density maps,choropleths,heatmaps, kernel density estimation, spatial graphs, Voronoi tesselation and and many more spatial visualizations. We describe geoplotlib design, functionalities and use cases.
This library is simple yet powerful API to generate geographical visualizations on OpenStreetMap tiles.
The geo-plotlib API is inspired by the matplotlib programming model and syntax, the de-facto standard for data visualization in python; this makes it easier for matplotlib users to get started.

The visualization canvas is initially empty, and each command adds a new layer of graphics. The geoplotlib window is displayed when show() is called. Alternatively, the map can be rendered to image file using savefig('filename'), or displayed inline in an IPython notebook using inline().

The biggest advantage of geoplotlib is that it is easy to download library with too less dependencies and easy to use and generate customizable maps. Having less dependencies makes the computation speed faster as well.

### Advanced Features
Additionally, there are more advanced features available in geoplotlib such as:

1. Animation with time stamp: animation feature work ONLY on time stamp data
2. Choropleth: each geographic unit is coloured to show a continuous variable
3. Custom layering: enables you to create and add custom layers

### References
http://www.marknagelberg.com/overview-python-and-non-python-mapping-tools-for-data-scientists/
https://www.researchgate.net/publication/305983877_Geoplotlib_a_Python_Toolbox_for_Visualizing_Geographical_Data
https://github.com/andrea-cuttone/geoplotlib
https://github.com/AntoineSueur/Geoplot-landslides
https://nbviewer.jupyter.org/github/amrrs/mapping_wifi_wigle_r_py/blob/master/Building%20Wifi%20Spots%20Map%20with%20Python%20and%20WiGLE.i
