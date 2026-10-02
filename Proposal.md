# Question:
 ### How do seasonal patterns differ among pollutants within Pittsburgh across a 9 year period?

# Website / Dataframe: 
	Source: Western Pennsylvania Regional Data Center

	URL: https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/4ab1e23f-3262-4bd3-adbf-f72f0119108b

	License: Creative Commons CCZero

	Date Found: September 6th

	Date Downloaded: September 10th

	File Size: 5.8 Mb

# Dataset Information

* There are about 87084 rows within the dataset

		(From date: Jan 1st 2016 → September 10th 2026)

* About 7573 rows imply some sort of health advisory and health effects descriptions; this can entail that those rows are days where the air quality index is at a more dangerous level and there needs to be a warning to advise people with health problems.

# Within each column:
* There is an id assigned (just numbered by how many rows in the dataset there are).

* There is a site which describes the neighborhood or location the data is being tested within Pittsburgh or within the borders of Pittsburgh (i.e. Lawrenceville, Flag Plaza, Harrison Township).

* There is a parameter that indicates what kind of chemical or substance is within the air (i.e. PM25B, CO, OZONE). 

* There is an index value that is shown as a numerical value, it describes the level and intensity of how polluted the air is (lower value is more clean, higher value is more polluted and dangerous). 

* There is a description that follows up with the index value, it basically describes whether the air quality is considered good, unhealthy for some people, or leading into the unhealthy and very unhealthy sectors. 

* Finally there are additional notes that regard a health warning based on the current AQI data, and the health side effects that come with it

# Grain of Dataset:

* One row represents one air quality measurement for a specific pollutant, at a specific site/location within or near Pittsburgh, at a specific point in time. Depending on how high the pollutant is measured, there can be additional descriptions on health advisory, and the health effects that can happen from too much exposure to unhealthy air quality.

* To support my row count, I have provided a box of code that computes and clarifies if each row in my dataset is unique, along with dropping duplicates of any rows. The output makes sure the number of rows equals the number of unique combinations; which in this case is true.

# What is the Comparison?

1) ### Date
	 (Group by seasonability (Over 9 years))

2) ### Index
	 (The numerical index pollution level OVERTIME (measurements))

3) ### Parameter
	 (To support the index level by grouping the index pollution level with the pollution title)

# Why did I find this interesting?

* Some days within a seasonable period can have extreme days where pollutants can dramatically alter the data for the month(s) or season. Finding data like this is quite interesting to me, as it allows me to stop and look at said bumps, and note their effects for my explanation. Also since this is a 9 year period, the data should be a bit more smooth to explain and you can minimize the amount of jumps from the data saying why each point is super important.

* If I don’t find a clear or complete trend of how pollutants patterns are, with the addition of  scattered pollutants throughout a 10 year period, I would believe the project to be slightly at a loss, but not entirely. This would be an attempt for me to work on my critical thinking skills, to organize my data and how I want my data to run. It’s probably very likely that something like this will happen, and it may or may not be a part of my conclusion. And even then, I can take a portion of my data and minimize the time period to either 5 years, or 3 years and follow through from there.

* This is an opportunity for me to work with a much larger set of data, and I would hope that the calculations I compute will be a bit more refined and not janky compared to a smaller set of data.