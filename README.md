# Z by HP Unlocked Challenge 1
Unlocked Challenge 1 - Data Visualization - Special thanks to Andrada Olteanu for helping design this tutorial!

## The Task
The challenge is to analyze the ecological data that is included in the repo. Can you create something that is visually appealing and meaningful? We would love to see you tell your own story from the data here. Be sure to also share it on your favorite social platforms with #ZUnlocked

## The Data

Source: https://www.fao.org/faostat/en/#data

* `temperature_change_data_11-29-2021.csv` - the change in temperature through time

	* Source: https://www.fao.org/faostat/en/#data/ET
	* Domain: Temperature Change
	* Area Code (ISO3)
	* Area: the country name (all countries available were selected)
	* Element: Temperature Change
	* Months: "Dec–Jan–Feb", "Mar–Apr–May", "Jun–Jul–Aug", "Sep–Oct–Nov", "Meteorological year"
	* Year: 1961 to 2020
	* Unit: °C
	* Value: the change in temperature
	* Flag Description: "Calculated Data" and "Data Not Available"

* `waste_disposal_data_11-29-2021.csv` - CO2 emissions tracking from incinerating (burning) waste disposal

	* Source: https://www.fao.org/faostat/en/#data/GW
	* Domain: Waste Disposal
	* Area Code (ISO3)
	* Area: the country name (all countries available were selected)
	* Element: Emissions (CO2)
	* Item: Incineration
	* Year: 1990 to 2019
	* Unit: kilotonnes
	* Value: CO2 emissions - absolute number
	* Flag Description: "Calculated Data" and "Aggregate, may include official, semi-official, estimated or calculated data"

* `energy_use_data_11-29-2021.csv` - CO2 emissions tracking from various energy industries

	* Source: https://www.fao.org/faostat/en/#data/GN
	* Domain: Energy Use
	* Area Code (ISO3)
	* Area: the country name (all countries available were selected)
	* Element: Emissions (CO2)
	* Item: 'Gas-Diesel oil', 'Motor Gasoline', 'Natural gas (including LNG)', 'Coal', 'Electricity', 'Liquefied petroleum gas (LPG)', 'Fuel oil', 'Gas-diesel oils used in fisheries', 'Fuel oil used in fisheries'
	* Year: 1970 to 2019
	* Unit: kilotonnes
	* Value: CO2 emissions - absolute number
	* Flag Description: "FAO estimate", "International reliable sources" and "Aggregate, may include official, semi-official, estimated or calculated data"

* `fires_data_11-29-2021.csv` - hectares of fires within forests and savannas

	* Source: https://www.fao.org/faostat/en/#data/GI
	* Domain: Fires
	* Area Code (ISO3)
	* Area: the country name (all countries available were selected)
	* Element: Burned Area
	* Item: 'Humid tropical forest', 'Other forest', 'Closed shrubland', 'Grassland', 'Open shrubland', 'Savanna', 'Woody savanna'
	* Year: 1990 to 2019
	* Unit: ha
	* Value: hectares of burned area (in absolute number)
	* Flag Description: "Calculated Data" and "Aggregate, may include official, semi-official, estimated or calculated data"

* `land_cover_data_11-30-2021.csv` - hectares of covered land by land type

	* Source: https://www.fao.org/faostat/en/#data/LC
	* Domain: Land Cover
	* Area Code (ISO3)
	* Area: the country name (all countries available were selected)
	* Element: MODIS land cover types based on the Land Cover Classification System
	* Item: 'Artificial surfaces (including urban and associated areas)', 'Herbaceous crops', 'Woody crops', 'Multiple or layered crops', 'Grassland', 'Tree-covered areas', 'Mangroves', 'Shrub-covered areas', 'Shrubs and/or herbaceous vegetation, aquatic or regularly flooded', 'Sparsely natural vegetated areas', 'Terrestrial barren land', 'Permanent snow and glaciers', 'Inland water bodies', 'Coastal water bodies and intertidal areas'
	* Year: 2001 to 2018
	* Unit: 1000 ha
	* Value: hectares of covered land
	* Flag Description: "Calculated Data", "Data not available" and "Aggregate, may include official, semi-official, estimated or calculated data"

## Where to Start
We have provided some starter code and a full tutorial video on how to create some basic visuals using matplotlib, seaborn, and plotly. These are great starting points for you to expand upon. 

## Further Inspiration for your Data Visualization

### How to create a great analysis

A dataset is very organic in nature. It's like a living, breathing organism. During an analysis you can find out some very interesting insights, some may even shock you! Other times the data shows the exact opposite thing that you might have expected. And sometimes it ... doesn't tell you anything really. But in that "nothingness" there is still a great deal to learn.

Hence, I would encourage you to start looking at the datasets with fresh eyes - free of any bias, hunch or belief that you might have. Don't try to "show" a conclusion that you might already think you have, as this usually limits your creativity.

### Double Check your Accuracy
Another very important thing is the accuracy of the visualization. Nothing is worse than creating an amazing, beautiful graph ... that shows innaccurate insights, information and conclusion. Be sure you create a double verification process, when you reiterate what you have already done and check yourself for any mistakes.

### Tools to help you
Lastly, try to have fun! Take inspiration from outside and bring it into your analysis. I like to look at movies, books, paintings, even interior design to inspire myself. Use color, use images, stickers, movement and pattern. I am leaving here some of my favorite sources and tools for inspiration:
* Canva for schemas, covers, images etc.: https://www.canva.com/
* Coolors for creating and combining the perfect color palette: https://coolors.co/
* How to use Markdown: https://spec-md.com/#note-eb0b0
* Create your own allerts: https://codepen.io/keikaavousi/pen/eYOmOpN
* Visualization Inspiration from Cedric Scherer: https://www.cedricscherer.com/
