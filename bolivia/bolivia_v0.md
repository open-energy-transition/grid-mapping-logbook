# Mapping Progress - Bolivia

## State of the Map
Please provide an screenshot of latest state of the grid.

![alt text](<images/Bolivia%202025-03-14%2009-26-23.png>)

## Timespan of Mapping
01.3.2025 - 13.3.2025

## Username of the Mappers Involved 
1. https://www.openstreetmap.org/user/Andreas%20Hernandez

## Were you focused on bulk or technical? 
- [x] Bulk mapping is finding towers and substations.
- [ ] Technical mapping is focused on metadata and the routing in between. 

## Mapping Environment  
- [x] [Grid Mapping Starter Kit](https://github.com/open-energy-transition/grid-mapping-starter-kit)
- [ ] Something else 

## Were the satellite images good enough in all areas for mapping? If no, in which area you were missing better data?
Satellite images were of good quality on bing imagery and sometimes Esri but slightly outdated. Many 2024 real-life developments could not be seen.

## Please provide a personal estimation of the grid quality before and after your mapping quality. What are success stories you can tell?
Before my mapping activity the grid map quality was relatively good. A few substations and lines were missing metadata, and several power lines had to be fixed.

**Success Stories**
1. The only current 500kv line in Bolivia was finalised and connected.
2. Many 115kv lines were mapped and corrected, and a 220kv line was connected.
3. A geojson hint layer official source was found, and helped mapping all major transmission lines until 2024.
4. Two in construction hydropower plants with total capacity of 300MW were found or correctly tagged

## In which area and in which aspects could the grid map been improved?
1. Once satellite data is available, a 220kv line could be finished and connected in the East
2. A 115kv line in the South could be mapped once satellite data is better.

## Mapping Strategies
Please provide the different mapping strategies you have used. 

- [x] Search for all **"Unfinished major power lines"** in Osmose and check if you are able to find new towers at the ende of the line.
- [x] Check if wind parks, solar farms, and power plants are connected to the transmission grid.
- [x] Ensure all transmission substations are connected to the grid.
- [x] Identify obvious gaps in the network topology from a national perspective.
- [x] Search for new lines parallel to existing ones and new lines starting from major central transmission substations.
- [x] Check for news reports on new substations and transmission lines that have become operational in recent years. LLMs like ChatGPT allow you to search in the local language: _"Please search for news about transmission lines or substation recently opened in country A. Please use the official language of the country for your search"_
- [x] Search for new substation records, national substation records and transmission line maps as a reference "hint" layer. LLMs like ChatGPT allow you to search in the local language: _"Please search for transmission lines or substation datasets in X. Please use the official language of the country for your search."_ For a curated list of datasets that may be useful, see [Awesome Electric Grid Mapping](https://github.com/open-energy-transition/Awesome-Electric-Grid-Mapping). The plugin [OpenData](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/OpenData) offers you the option of using a variety of different data sets in JOSM.
- [ ] Other strategies here!

## Mapping Datasets
What mapping datasets have you used as a hint layer? Please provide links to the data.
1. [Instructivos de restitución del SIN (Sistema Interconectado Nacional) de **Bolivia**](https://www.cndc.bo/media/archivos/normas/Instructivos_de_Restitucion_del_SIN.pdf)
2. [Subestaciones en **Bolivia**](https://www.scribd.com/document/425875074/Subestaciones-en-Bolivia)
3. [Transmission grid map of **Bolivia**2024](https://geoportal.mhe.gob.bo/layers/geonode:transmision_sin_20220810/layer_export#/)

## Map Progress
![alt text](</images/DeltaBolivia.png>)
