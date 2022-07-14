# US-State-House-Elections

The goal of this project was to be able to predict election results from the 2016 and 2020 US State House of Representative Elections reasonably well and thereby gain experience in an end to end Data Science workflow (find it under **_US State House Elections 2016 + 2020.ipynb_**).

The target variable for 2016 is webscraped from Ballotpedia (www.ballotpedia.com). As for 2020 webscraping wasn't possible the data was extracted from the MIT Election and Science Lab dataset (https://electionlab.mit.edu/). The notebooks with this process can be found under "2016 Target Data Ballotpedia", "2020 Target Data".

Data for the features are from the US Census Bureau (https://data.census.gov/cedsci/) for the years 2016 and 2020. Every possibly useful information on State election district level was gathered. Certainly there could have been more predictive variables than some of the ones used. However, it's almost impossible to gather this data on the district level for State elections.

As the unit of measurement is on district level every value for a certain district represents how many percent of the disctrict population takes on a certain characteristic. Some of the variables don't show percentages, but rather median values for the respective district. The process of data gathering can be found under "Census Data Preparation 2016" and "Census Data Preparation 2020".
