# Beer 4 the Road

**by: Pritpal Bhangu, Sean Bernard, Andre Loukrezis & Bridget Weill**

[Presentation Slides](https://docs.google.com/presentation/d/1j5LYrznqsJzO7ANX2bR8IL3AXGds6GPl9qsd7yKjEDw/edit?usp=sharing)



## Project Objective


In this project, we looked at beer and brewery data in the United States.  Our objective was to  to determine a fun road trip where we visited cities and states that had plenty of breweries and matched our beer preferences.  We produced descriptive statistics such as which states/regionsr have the most breweries/wineries, which states/regions produce beers with the highest ABV, etc.  

## Motivations

As a group, we were interested in learning more about breweries across United States.  We also wanted to learn more about the types of beer as our group has our own unique preferences to beer with regards to taste, abv, etc. Another motivation was to identify areas in the United States that cater to each of our specific beer/wine preferences. We were able to break it down by region, state, and city.  Ultimately, we felt diving into this data would be a solid starting point for deciding where the best places to travel to would be based on our own individual preferences.

## Data Source

The data used in this project comes from the following: 

- Brewery and Beer Types Data - https://www.kaggle.com/nickhould/craft-cans
- Wine Data - https://www.kaggle.com/pabloa/wine-magazine/data

**Additional references:** 

1. set up a basic pie chart in matplotlib  https://matplotlib.org/3.1.1/gallery/pie_and_polar_charts/pie_features.html
2. show the values of each beer type https://stackoverflow.com/questions/41088236/how-to-have-actual-values-in-matplotlib-pie-chart-displayed-python?rq=1
3. info on craft beer styles https://www.morebeer.com/articles/Popular-Craft-Beer-Styles
4. info on craft beer styles https://learn.kegerator.com/american-ipa/


## Library Glossary


**Pandas:** 
is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

**Numpy:** 
is the fundamental package for scientific computing with Python. It contains among other things:

a powerful N-dimensional array object

sophisticated (broadcasting) functions

tools for integrating C/C++ and Fortran code

useful linear algebra, Fourier transform, and random number capabilities

Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

**Matplotlib:**
is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.

Python’s fundamental plotting library (pg. 50 Pandas Textbook)

**Seaborn:**  

a library that builds on matplotlib by providing a higher-level interface for statistical graphics. It provides an interface to produce prettier and more complex visualizations with fewer lines of code.

The seaborn library is tightly integrated with Pandas and the rest of the PyData stack (numpy, scipy, statsmodels), making visualizations from any part of the data analysis process a breeze. Since seaborn is built on top of matplotlib, the user still has the ability to fine-tune the visualizations. (pg. 61 Pandas Textbook)

## Challenges


### Working with a limited dataset.
- the breweries data was incomplete, as it technically did not have every single registered brewewry in the United States.
- the beer data did not have sufficient enough data on the IBU of each beer.  Only a small fraction of the data had this metric.  It would've been nice to add this layer to our analysis based on people's taste/bitterness preference.
- we would've liked to have had latitude/longitude coordinates for the breweries as this would've enhanced our exploration into the geographical data.

### Identifying a Project Scope and Deciding on a Story to Tell
- we ran descriptive statistics and discussed different approaches to our analysis
- we ultimately had to be realistic and figure out what the best story was based on our analysis
- we had to cancel previous ideas due to scope/timeline/skillset 

### Importing and Using Geopandas.
- figuring out how to incorporate geopandas was equally fun and challennging. 
- we were able to create chloropeth heatmaps to visualize states with the most breweries, but we had to create additional dataframes due to lack of more detailed geographical data.

### Figuring out GitHub Process.
- as a team, we had to agree on a process where we could share our work and ensure it is pushed properly/stored in the repository. 

### Difficult to Visualize Ideas.
- do not have the skillset yet to create complex visualizations and build functions based on our ideas.
- it was challenging when we had an idea but weren't able to produce it based on our skillset.


## Lessons Learned
- everything with Python is trial and error.
- explore the dataset more before deciding on analysis.
- look at other options and try out different datasets.