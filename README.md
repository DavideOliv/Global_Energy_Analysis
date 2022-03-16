## Global Power Plant and Consumption and Use of Energy 

### Abstract:

An affordable, reliable, and environmentally sustainable power sector is central to modern society.
Governments, utilities, and companies make decisions that both affect and depend on the power sector.
For example, if governments apply a carbon price to electricity generation, it changes how plants run and which plants are built over time.
On the other hand, each new plant affects the electricity generation mix, the reliability of the system, and system emissions.
Plants also have significant impact on climate change, through carbon dioxide (CO2) emissions; on water stress, through water withdrawal and consumption; and on air quality, through sulfur oxides (SOx), nitrogen oxides (NOx), and particulate matter (PM) emissions.

The aim is to analyze and estimate the consumption and use of energy in the world, comparing the renawable energy with nuclear energy.

### Dataset
In this project have been used 4 dataset:
* **global_power_plant_database.csv**

	- `country` (text): 3 character country code corresponding to the ISO 3166-1 alpha-3 specification 
	- `country_long` (text): longer form of the country designation
	- `name` (text): name or title of the power plant, generally in Romanized form
	- `gppd_idnr` (text): 10 or 12 character identifier for the power plant
	- `capacity_mw` (number): electrical generating capacity in megawatts
	- `latitude` (number): geolocation in decimal degrees; WGS84 (EPSG:4326)
	- `longitude` (number): geolocation in decimal degrees; WGS84 (EPSG:4326)
	- `primary_fuel` (text): energy source used in primary electricity generation or export
	- `other_fuel1` (text): energy source used in electricity generation or export
	- `other_fuel2` (text): energy source used in electricity generation or export
	- `other_fuel3` (text): energy source used in electricity generation or export
	- `commissioning_year` (number): year of plant operation, weighted by unit-capacity when data is available
	- `owner` (text): majority shareholder of the power plant, generally in Romanized form
	- `source` (text): entity reporting the data; could be an organization, report, or document, generally in Romanized form
	- `url` (text): web document corresponding to the `source` field
	- `geolocation_source` (text): attribution for geolocation information
	- `wepp_id` (text): a reference to a unique plant identifier in the widely-used PLATTS-WEPP database.
	- `year_of_capacity_data` (number): year the capacity information was reported
	- `generation_gwh_2013` (number): electricity generation in gigawatt-hours reported for the year 2013
	- `generation_gwh_2014` (number): electricity generation in gigawatt-hours reported for the year 2014
	- `generation_gwh_2015` (number): electricity generation in gigawatt-hours reported for the year 2015
	- `generation_gwh_2016` (number): electricity generation in gigawatt-hours reported for the year 2016
	- `generation_gwh_2017` (number): electricity generation in gigawatt-hours reported for the year 2017
	- `generation_gwh_2018` (number): electricity generation in gigawatt-hours reported for the year 2018
	- `generation_gwh_2019` (number): electricity generation in gigawatt-hours reported for the year 2019
	- `generation_data_source` (text): attribution for the reported generation information
	- `estimated_generation_gwh_2013` (number): estimated electricity generation in gigawatt-hours for the year 2013 
	- `estimated_generation_gwh_2014` (number): estimated electricity generation in gigawatt-hours for the year 2014 
	- `estimated_generation_gwh_2015` (number): estimated electricity generation in gigawatt-hours for the year 2015 
	- `estimated_generation_gwh_2016` (number): estimated electricity generation in gigawatt-hours for the year 2016
	- `estimated_generation_gwh_2017` (number): estimated electricity generation in gigawatt-hours for the year 2017 
	- `estimated_generation_note_2013` (text): label of the model/method used to estimate generation for the year 2013 
	- `estimated_generation_note_2014` (text): label of the model/method used to estimate generation for the year 2014 
	- `estimated_generation_note_2015` (text): label of the model/method used to estimate generation for the year 2015 
	- `estimated_generation_note_2016` (text): label of the model/method used to estimate generation for the year 2016 
	- `estimated_generation_note_2017` (text): label of the model/method used to estimate generation for the year 2017 
	- 
* **Primary-energy-consumption-from-fossilfuels-nuclear-renewables.csv**
	- `Entity` : country 
	- `Code`: code country 
 	- `Year`
	- `Fossil fuels` : % sub energy
	- `Renewables` : % sub energy
	- `Nuclear` : % sub energy

* **share-elec-produc-by-source.csv**
Electric Energy produced for each country
	- `Entity` : country 
	- `Code`: code country 
 	- `Year`
	-`Coal` : % electricity 
	- `Gas` : % electricity 
	- `Hydro` : % electricity 
	- `Solar` : % electricity
	- `Wind` : % electricity
	- `Oil` : % electricity
	- `Nuclear` : % electricity

* **share-energy-consum-by-source.csv**
Electric Energy consumed for each continent
	- `Entity` : country 
	- `Code`: code country 
 	- `Year`
	-`Coal` : % electricity 
	- `Gas` : % electricity 
	- `Hydro` : % electricity 
	- `Solar` : % electricity
	- `Wind` : % electricity
	- `Oil` : % electricity
	- `Nuclear` : % electricity







