# Kenya 

<span style="color:red">
**This page is planed to be moved on the OpenStreetMap wiki.**   
Please create the appropriate page here: https://wiki.openstreetmap.org/wiki/Power_networks and consider moving all relevant information there.
</span>

## Map Progress
Please provide an image of changes made using the following overpass script provided [here](https://raw.githubusercontent.com/open-energy-transition/grid-mapping-starter-kit/refs/heads/main/scripts/mapping_progress.overpassql).
![alt text](<images/delta-kenya-2025-03-14-10-22-52.png>)

## Timespan of Mapping
26.12.2024 - 14.3.2025

## Username of the Mappers Involved 
1. https://www.openstreetmap.org/user/Tobias%20Augspurger

## Were you focused on bulk or technical? 
- [x] Bulk mapping is finding towers and substations.
- [ ] Technical mapping is focused on metadata and the routing in between. 

## Mapping Environment  

- [x] [Grid Mapping Starter Kit](https://github.com/open-energy-transition/grid-mapping-starter-kit)
- [ ] Something else 

## Were the satellite images good enough in all areas for mapping? If no, in which area you were missing better data?
The satellite images were good enough in all regions but about 2 years old. No problems with clouds or total missing of high resolution satellite data.

## Please provide a personal estimation of the grid quality before and after your mapping quality. What are success stories you can tell?
Before my mapping activity the grid map quality was quite mediocre. A lot of substations were missing and because of the significant growth of the transmission grid in this region over the last 5 years a lot of new lines need to be created. 
Some of the larger lines like the connection to Tanzania did not follow exactly the power towers visible in satellite images. After the mapping most of the grid does fit to maps of the TSO. In general the quality of the grid look very good now. 

**Success Stories** 
1. Connected the transmission grid between Kenya and Tanzania
2. Connected some remote solar parks and industrial areas. 

## In which area and in which aspects could the grid map been improved?
1. For some lines the voltages are still missing.
2. Some lines next to the victoria lake are visible in official maps but could not been mapped. 
3. Some general routing issues still exists. 

## Mapping Strategies
Please provide the different mapping strategies you have used. 

- [x] Search for all **"Unfinished major power lines"** in Osmose and check if you are able to find new towers at the ende of the line.
- [x] Check if wind parks, solar farms, and power plants are connected to the transmission grid.
- [x] Ensure all transmission substations are connected to the grid.
- [x] Identify obvious gaps in the network topology from a national perspective.
- [x] Search for new lines parallel to existing ones and new lines starting from major central transmission substations.
- [x] Check for news reports on new substations and transmission lines that have become operational in recent years. LLMs like ChatGPT allow you to search in the local language: _"Please search for news about transmission lines or substation recently opened in country A. Please use the official language of the country for your search"_
- [x] Search for new substation records and national substation records as a reference "hint" layer. LLMs like ChatGPT allow you to search in the local language: _"Please search for transmission lines or substation datasets in X. Please use the official language of the country for your search."_ For a curated list of datasets that may be useful, see [Awesome Electric Grid Mapping](https://github.com/open-energy-transition/Awesome-Electric-Grid-Mapping). The plugin [OpenData](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/OpenData) offers you the option of using a variety of different data sets in JOSM.
- [ ] Other strategies here!

## Mapping Datasets
What mapping datasets have you used as a hint layer? Please provide links to the data.

1. [KETRACO Transmission Master Plan 2023/2042 of **Kenya**](https://drive.google.com/file/d/1p_j3pJT4sdOcxo1Msfo180yLEQYjj8hA/view)
2. [Kenya - Primary Substations](https://energydata.info/dataset/kenya-primary-substations)

## State of the Map
Please provide an screenshot of latest state of the grid.

![alt text](<images/kenya-2025-03-14-10-25-39.png>)

