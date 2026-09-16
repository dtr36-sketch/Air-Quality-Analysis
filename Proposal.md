Question: How do seasonal patterns differ among pollutants within Pittsburgh across a 10 year period?

Website / Dataframe: 
	Source: Western Pennsylvania Regional Data Center
	URL: https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/4ab1e23f-3262-4bd3-adbf-f72f0119108b
	License: Creative Commons CCZero
	Date Found: September 6th
	Date Downloaded: September 10th
	File Size: 5.8 Mb

Dataset Information

There are about 87084 rows within the dataset (From date: Jan 1st 2016 → September 10th 2026)
About 7573 rows imply some sort of health advisory and health effects descriptions; this can entail that those rows are days where the air quality index is at a more dangerous level and there needs to be a warning to advise people with health problems.

Within each column:
There is an id assigned (just numbered by how many rows in the dataset there are). 
There is a site which describes the neighborhood or location the data is being tested within Pittsburgh or within the borders of Pittsburgh (i.e. Lawrenceville, Flag Plaza, Harrison Township).
 There is a parameter that indicates what kind of chemical or substance is within the air (i.e. PM25B, CO, OZONE). 
There is an index value that is shown as a numerical value, it describes the level and intensity of how polluted the air is (lower value is more clean, higher value is more polluted and dangerous). 
There is a description that follows up with the index value, it basically describes whether the air quality is considered good, unhealthy for some people, or leading into the unhealthy and very unhealthy sectors. 
Finally there are additional notes that regard a health warning based on the current AQI data, and the health side effects that come with it

Grain of Dataset:

One row represents one air quality measurement for a specific pollutant, at a specific site/location within or near Pittsburgh, at a specific point in time. Depending on how high the pollutant is measured, there can be additional descriptions on health advisory, and the health effects that can happen from too much exposure to unhealthy air quality.

To support my row count, I have provided a box of code that computes and clarifies if each row in my dataset is unique, along with dropping duplicates of any rows. The output makes sure the number of rows equals the number of unique combinations; which in this case is true.

What is the Comparison?

Date (Group by seasonability (Over 10 years))
Index (The numerical index pollution level OVERTIME (measurements))
Parameter (To support the index level by grouping the index pollution level with the pollution title)

Why did I find this interesting?

Some days within a seasonable period can have extreme days where pollutants can dramatically alter the data for the month(s) or season. Finding data like this is quite interesting to me, as it allows me to stop and look at said bumps, and note their effects for my explanation. Also since this is a 10 year period, the data should be a bit more smooth to explain and you can minimize the amount of jumps from the data saying why each point is super important.

If I don’t find a clear or complete trend of how pollutants patterns are, with the addition of  scattered pollutants throughout a 10 year period, I would believe the project to be slightly at a loss, but not entirely. This would be an attempt for me to work on my critical thinking skills, to organize my data and how I want my data to run. It’s probably very likely that something like this will happen, and it may or may not be a part of my conclusion. And even then, I can take a portion of my data and minimize the time period to either 5 years, or 3 years and follow through from there.

This is an opportunity for me to work with a much larger set of data, and I would hope that the calculations I compute will be a bit more refined and not janky compared to a smaller set of data.



Objective
Compute the average pollutant levels for each season




SAMPLE CLAUDE PROPOSAL:

Research Proposal: Seasonal Patterns of Air Pollutants in Pittsburgh (2016–2026)
Research Question
How do seasonal patterns differ among pollutants within Pittsburgh across a 10-year period?
Dataset




Source
Western Pennsylvania Regional Data Center (WPRDC)
Dataset
Allegheny County Air Quality
URL
https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/4ab1e23f-3262-4bd3-adbf-f72f0119108b
License
Creative Commons CC0 (public domain)
Date Found
September 6
Date Downloaded
September 10
File Size
5.8 MB

Dataset Overview
The dataset contains 87,084 rows spanning January 1, 2016 through September 10, 2026 — just over ten years of daily air quality monitoring across the Pittsburgh region. Of those rows, 7,573 (about 8.7%) carry a health advisory and an accompanying health-effects description, meaning the recorded pollutant level on that day was high enough to warrant a public warning.
Columns:
_id — a sequential row identifier
date — the date of the measurement
site — the monitoring station's neighborhood or location (e.g., Lawrenceville, Flag Plaza, Harrison Township)
parameter — the specific pollutant or measurement instrument (e.g., PM25B, CO, OZONE)
index_value — a numerical air quality index value; lower means cleaner air, higher means more polluted/dangerous
description — the categorical air quality rating tied to the index value (Good, Moderate, Unhealthy for Sensitive Groups, Unhealthy, Very Unhealthy)
health_advisory / health_effects — populated only when conditions warrant a warning, describing the advisory and its associated health risks
Grain of the Dataset
One row represents one air quality measurement for a specific pollutant, at a specific monitoring site, on a specific date. Depending on how high that pollutant reading is, the row may also carry a health advisory and a description of possible health effects.
To confirm this grain, I ran a uniqueness check that compares the row count against the count of unique row combinations after dropping duplicates. Both counts matched (87,084 = 87,084), confirming there are no duplicate records and that each row is indeed a distinct measurement event.
What Is Being Compared
Date, grouped by season, across the full 10-year window
Index value — the numerical pollution level, tracked over time
Parameter — the pollutant type, used to break the index value down by what is actually being measured
Together, these three fields let me ask: does each pollutant have its own seasonal "personality," or do they all rise and fall together?
Why I Find This Interesting
Some days within a given season can carry extreme, outlier readings that noticeably shift the data for an entire month or season. I find it genuinely interesting to locate these bumps, isolate them, and think through what likely caused them — a wildfire smoke event, a heat inversion, an industrial incident, and so on — rather than letting them blend anonymously into an average. Because this project spans ten years rather than one or two, I expect the long-run seasonal trends to come through more smoothly, which should make it easier to explain why a given point matters instead of getting lost re-explaining every single jump in the data.
If I don't end up finding a clean, complete seasonal trend for every pollutant — and given the scattering visible even in the preliminary numbers above, that is a real possibility — I don't think the project is a failure. Part of the point of this exercise is building my own critical thinking around organizing messy, real-world data and being honest about where it does and doesn't cooperate. If the full ten-year window turns out to be too noisy or too uneven across pollutants, I can scope down to a 5-year or 3-year window and rebuild the seasonal comparison from there.
Finally, this is a chance to work with a genuinely large dataset (87,000+ rows) rather than a toy-sized one. I expect that the averages, seasonal breakdowns, and trend lines I compute here will be more stable and less "janky" than what I'd get from a smaller sample, simply because there is more data to smooth out individual bad days.




