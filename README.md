# [Crime in Vancouver, BC DataViz](https://github.com/SumaiaParveen/Vancouver-Crime-DataViz/blob/main/Van_crime_Viz.ipynb)

## ABOUT THE DATA

Source: [Vancouver Open Data Catalogue.](https://geodash.vpd.ca/opendata/)

Attribute Information:

* TYPE: The type of crime activities
  - BNE Commercial: (Commercial Break and Enter) Breaking and entering into a commercial property with intent to commit an offence
  - BNE Residential/Other: (Residential Break and Enter) Breaking and entering into a dwelling/house/apartment/garage with intent to commit an offence
  - Vehicle Collision or Pedestrian Struck (with Fatality): Includes primarily pedestrian or cyclist struck and killed by a vehicle. It also includes vehicle to vehicle fatal     accidents, however these incidents are fewer in number when compared to the overall data set. Note: There is no neighbourhood information.
  - Vehicle Collision or Pedestrian Struck (with Injury): Includes all categories of vehicle involved accidents with injuries. This includes pedestrian and cyclist involved incidents with injuries. Note: There is no neighbourhood information
  - Homicide: A person, directly or indirectly, by any means, causes the death of another person.
  - Mischief: A person commits mischief that willfully causes malicious destruction, damage, or defacement of property. This also includes any public mischief towards another person.
  - Offence Against a Person: An attack on a person causing harm that may include usage of a weapon.
  - Other Theft: Theft of property that includes personal items (purse, wallet, cellphone, laptop, etc.), bicycle, etc.
  - Theft from Vehicle: Theft of property from a vehicle
  - Theft of Vehicle: Theft of a vehicle, motorcycle, or any motor vehicle
  - Theft of Bicycle: Theft of a bicycle
* YEAR: A four-digit field that indicates the year when the reported crime activity occurred

* MONTH: A numeric field that indicates the month when the reported crime activity occurred
* DAY: A two-digit field that indicates the day of the month when the reported crime activity occurred
* HOUR: A two-digit field that indicates the hour time (in 24 hours format) when the reported crime activity occurred. Note: This information is based on the findings of the police investigation. **No time information is provided for Offences Against a Person crime type.**
* MINUTE: A two-digit field that indicates the minute when the reported crime activity occurred. Note: This information is based on the findings of the police investigation. **No time information is provided for Offences Against a Person crime type.**
* HUNDRED_BLOCK: Generalized location of the report crime activity. **Note: Locations for reported incidents involving Offences Against a Person have been deliberately randomized to several blocks and offset to an intersection. No time or street location name is provided for these offences.** For property related offences, the VPD has provided the location to the hundred block of these incidents within the general area of the block. All data must be considered offset and users should not interpret any locations as related to a specific person or specific property. Coordinates data for records with “Offset to Protect Privacy” was not disclosed to provide privacy protection. X NK_LOC ST is default location value used for incidents with unknown location and is geolocated to 312 Main Street
* NEIGHBOURHOOD: The Vancouver Police Department uses the Statistics Canada definition of neighbourhoods within municipalities. Neighbourhoods within the City of Vancouver are based on the census tract (CT) concept within census metropolitanarea (CMA). The Musqueam Indian Band is located in the southwest corner of the City of Vancouver. There is a service agreement between Musqueam and the City of Vancouver, where the City provides municipal services such as policing. As a result, Musqueam crime data is included with the VPD Open Data.
* X: *Coordinate values are projected in UTM Zone 10*. All data must be considered offset and users should not interpret any locations as related to a specific person or specific property.
* Y: *Coordinate values are projected in UTM Zone 10*. All data must be considered offset and users should not interpret any locations as related to a specific person or specific property.

## What are shown in these infographics?

As I have moved to Vancouver, British Columbia recently, I want to know about the Crime and Safety Situation in different parts of the city. In that way, I will be able to decide on a neighborhood where we will rent an apartment. I have done brief research online and Sunset can be a good fit for us. I want to see the overall crime situation as well as the types and frequency of occurrence of these crimes in Sunset. let's do this!

## Libraries used

- Matplotlib 
- Seaborn
- Folium
- Bqplot

### Some Highlights

![Test Image 1](https://github.com/SumaiaParveen/Vancouver-Crime-DataViz/blob/main/images/output_28_1.png)
![Test Image 1](https://github.com/SumaiaParveen/Vancouver-Crime-DataViz/blob/main/images/output_40_0.png)

![Test Image 1](https://github.com/SumaiaParveen/Vancouver-Crime-DataViz/blob/main/images/output_46_0.png)

##### Location of 'Theft from Vehicle' in Sunset in October 2020

![Test Image 1](https://github.com/SumaiaParveen/Vancouver-Crime-DataViz/blob/main/images/Capture.JPG)


