# UFO Sightings Analysis

### Project Overview
This projects aims to explore trends and patterns in UFO sightings from NUFORC's UFO Sighthings Dataset. By analyzing aspects of the UFO Sightings Data, I hope to answer the following the questions:

1. Which countries report the most UFO Sightings?
2. How has number of sightings changed overtime?
3. What are the most commonly reported UFO shape?
4. What time of day and month have the highest probability of UFO sightings?

### Data Sources

Ufo Sightings Data: The primary dataset used for this analysis is the "ufo_sightings_scrubbed.csv", containing detailed records of sightings reported to NUFORC up to 2014

### Tools
**Languages:**
* Python (Data Analysis and Visualization)

**Libraries**
* Numpy (Numerical Operation)
* Pandas (Data Cleaning)
* Matplotlib/Seaborn/Plotly (Data Visualization)

### Data Cleaning
In the data cleaning phase, I performed the following tasks:
1. Dropping irrelevant columns
2. Removed duplicated data
3. Reformatting country column
4. Handling missing values in country column
5. Converted data into appropriate formats (e.g., datetime)
6. Split combined datetime into separate date and time columns
7. Removed extreme Outliers

### Exploratory Data Analysis
To answer the questions, I used the following plots:
* Cloropleth Map to show all the countries and how much UFO sightings were reported there
* Line graph to show how UFO sightings changed overtime
* Bar charts to show the distribution of UFO sighings based on different variables (i.e hour of day, month, etc)
* Heatmap to show the values of the pair of variables (hour of the day and month) which yields the highest reports of UFO sightings

### Findings
* United States reported the most UFO sightings by a significant amount, followed by Canada, followed by Canada, Australia, United Kingdom then India
* UFO sightings remainded relatively low until 1990, but it sharply decreased between 2012-2014
* Only United States, Canada, Australia, United Kingdom and India showed a consistent increase of UFO sightings overtime
* 'light' was the most reported which accounted for 20.5% of total shapes, indicating that most people saw bright objects
* 'triangle' and 'circle' (top 2 and 3 respectively and half the reports of 'light' each) were distinct shapes with the most reports
* The best time to see a UFO is at July between 22:00 - 22:59
* Most sightings (56%) occurred between 19:00 and midnight, and in the second half of the year.

### Limitations
* Since the  majority of the sightings came from the United States, the analysis is highly biased toward US trends.
* Other countries, while present in the dataset, contribute far fewer reports, limiting the generalizability of conclusions beyond the US
