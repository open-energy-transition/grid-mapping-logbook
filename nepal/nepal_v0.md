# Nepal

**This page is planed to be moved on the OpenStreetMap wiki.**   
Please create the appropriate page here: https://wiki.openstreetmap.org/wiki/Power_networks and consider moving all relevant information there.

## Map Progress
Please provide an image of changes made using the following overpass script provided [here](https://github.com/open-energy-transition/KPI-OSM/tree/main/before_and_after).<br>

![alt text](https://github.com/open-energy-transition/grid-mapping-logbook/blob/main/nepal/images/Screenshot%20from%202025-04-07%2012-39-17.png)

## Timespan of Mapping
19.03.2025 - 24.03.2025

## Username of the Mappers Involved 
1. https://www.openstreetmap.org/user/Andreas%20Hernandez

## Were you focused on bulk or technical? 
- [x] Bulk mapping is finding towers and substations.
- [ ] Technical mapping is focused on metadata and the routing in between. 

## Mapping Environment  

- [x] [Grid Mapping Starter Kit](https://github.com/open-energy-transition/grid-mapping-starter-kit)
- [ ] Something else 

## Were the satellite images good enough in all areas for mapping? If no, in which area you were missing better data?
The most up to date satellite imagery was Esri. Satellite images were relatively up-to-date, although certain areas could not be finished due to old imagery. 
However, I would say Nepal is particularly hard to map due to the terrain, and satellite imagery distortions.

## Please provide a personal estimation of the grid quality before and after your mapping quality. What are success stories you can tell?
The grid was not mapped much before. The total energy capacity was much lower, the main hydropower station was not mapped for example. Many lines were unmapped, and a very large number substations were missing.
Now, the grid is almost up-to-date with what can be done with the current satellite imagery. Below I have added the lines that need to be finished when satellite data is updated, or lines which are very difficult to map.

**Success Stories** 
1. Found and mapped a 132kv interconnection with India.
2. Added 3134 towers (1/3 of all towers mapped in Nepal), and almost 50 substations (either found, or important metadata was added).
3. Mapped numerous power plants adding up to 980 MW, which is 78% of Nepal's total capacity mapped in OSM.
4. Finalised and found many lines, including 400kv lines.
5. Connected two substations to each other which were important for the connectivity of the entire grid.

## In which area and in which aspects could the grid map been improved?
The following improvements can be made (finishing lines when satellite data is better):
1) Jhimruk dam to Lamahi substation 132kv
2) Finish Motipur-Sandikharka-Tamgash 132kv line
3) Finish New Butwal-Kusma 220kv line
5) Udipur-Kritipur 132kv 
6) Middle Marsyangadi to Upper Marsyangadi 132kv line
7) Inaruwa to Basantapur 220kv not finished
8) Baneshwor 220kv to Basantapur
9) Basantapur to Dhungesangu 220kv
10) Tumnlingtar to Sitalpati 220kv
11) Mirchaiya to Tingla 132kv
12) Barhabise to New Khimti 400kv (a few towers)
13) Lamosangu substation to Barhabisse 132kv
15) 132kv line from Kohallpur to Surkhet
16) 400kv line Barhabise to Lapsiphedi
18) Hetauda line which goes
19) Dhalkebar power line unfinished 

Tingla 132kv, Dhalkebar 400kv substation could be cleaned up. Hydropower stations could be better mapped.

## Misc
Beware with dates in official Nepalese papers as they do not use the same Gregorian calendar (2025). 

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

1. [Nepal Electricity Authority Annual Report](https://www.nea.org.np/admin/assets/uploads/annual_publications/NEA_Annual_Report_2081_New.pdf) - (**Includes capacity data**)

This hint layer includes a map of the grid and a complete list of all projects.

## State of the Map and progress
Please provide a screenshot of latest state of the grid.

![alt text](https://github.com/open-energy-transition/grid-mapping-logbook/blob/main/nepal/images/Screenshot%20from%202025-04-07%2012-39-42.png)

Please provide a screeshot of the state of the grid before you mapped it.

![alt text](https://github.com/open-energy-transition/grid-mapping-logbook/blob/main/nepal/images/Screenshot%20from%202025-04-11%2015-15-21.png)

