## Guiding Question
What commonalities can be found between traffic accident hotspots in the US?

- **Source 1: US Traffic Accidents (2016-2021)**
	- Where did I find it: Kaggle
	- Who collects it: Sobhan Moosavi is a Data Scientist at Lyft that collects and maintains the data through multiple data-streaming APIs.
	- Why it was created: The database was intended solely for research & academic purposes, and its license forbids it from being used in a corporate setting. It's open source and thus is free to the public to use.
	- What does a case represent?: One case is one car accident, and all the variables are different pieces of information regarding when & where the accident occurred, what the conditions were during the accident, etc.
	- I plan on using the city information, the GPS coordinates, some (but not all) of the weather/visibility information and lots of information regarding surrounding infrastructure.

- **Source 2: US City Density statistics**
	- Where did I find it: I found it on simplemaps.com
	- Who collects it: data analysts at simplemaps.com source the data from U.S. Geological Survey, The American Community Survery and the U.S. Census Bureau.
	- Why was it created: The database is meant to give people a clean, finished database for geospatial data analytical applications. This is the free version, but the paid version is significantly more vast and includes even the smallest towns in the country.
	- What does a case represent?: One case represents a single city, and I will use it as a reference to look for an association between population density and accidents at various different severity levels.
	- Which variables are helpful?: I plan on using the city/state names, but also their GPS coordinates, and population densities. This database will primarily be used to map out hotspots for population density, and then from there I will be mapping out the GPS coordinates of accidents in those areas to look for associations between those two variables.