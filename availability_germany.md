
## Lidar availability - Germany

Geodata collection, administration and publication in Germany is predominantly organized in federal structures by the land surveying and cadaster authorities of the 16 federal states. Although the *Working Committee of the surveying authorities of the states of the Federal Republic of Germany* (AdV) defines guidelines and standards there is still a variety of different data types in the realm of laser scanning data. For applications on a broader scale beyond state boundaries it is essential to know the data availability. Hence, information on federal ALS was collected from federal mapping agencies' websites and other source such as personal and Email comunication.


*Comparison of available ALS data in Germany by state*

| Federal State | Cost (min)[^1] | Cost (max)[^2] | Year (from)[^3] | Year (to)[^4] | Point Density[^5] | Format | CRS (EPSG) |
|---|---|---|---|---|---|---|---|
| Baden-Württemberg | 10 | 80 | 2016 | 2021 | 8 | LAZ 1.2 | 25832 |
| Bavaria | 0 | 0 | 2011 | 2021 | 1-4 | LAZ 1.2 | 25832 |
| Berlin | 0 | 0 | 2021 | 2021 | 10 | LAS 1.4 | 25833 |
| Brandenburg | 0 | 0 | 2017 | 2022 | 5 | LAZ 1.4 | 25833 |
| Bremen | 80 | 80 | 2017 | 2017 | ? | ? | 25832 |
| Hamburg | ? | ? | 2020 | 2020 | ? | ? | 25832 |
| Hesse | 0 | 0 | 2009 | 2020 | 4 | LAS 1.3 | 25832 |
| Mecklenburg-Western Pomerania | 10 | 80 | 2012 | 2022 | 2-5 | LAZ 1.2 | 25833 |
| Lower Saxony | 3,75 | 30 | 2015 | 2021 | 4 | LAZ 1.2 | 25832 |
| North Rhine-Westphalia | 0 | 0 | 2018 | 2022 | 4-10 | LAZ 1.2 | 25832 |
| Rhineland-Palatinate | 25 | 100 | 2014 | 2022 | 4 | LAZ 1.2 | 25832 |
| Saarland | 120 | 120 | 2016 | 2016 | 4 | LAS 1.2 | 25832 |
| Saxony | 0 | 0 | 2015 | 2022 | 4 | LAZ 1.2 | 25833 |
| Saxony-Anhalt | 0 | 0 | 2009 | 2023 | 3-5 | LAZ 1.2 | 25832 |
| Schleswig-Holstein | ? | ? | ? | ? | 3-5 | ? | 25832 |
| Thuringia | 0 | 0 | 2017 | 2022 | 4 | LAZ 1.4 | 25832 |

[^1]: in € per km² (with volume discount; plus processing fee)
[^2]: in € per km² (plus processing fee)
[^3]: oldest data for statewide coverage
[^4]: newsest data for statewide coverage
[^5]: specified minimum number of points per m²


### National

According to https://doi.org/10.3390/ijgi6080243 "topographic databases maintained by national mapping agencies are currently the most common nationwide data sets in geo-information", however this is not true for Germany. Until now there is no single data set which is available for entire Germany. However, there are plans to generate such data. The project [Digital Twin Germany](https://www.business-geomatics.com/2022/11/17/zwillinge-gross-gedacht/) aims to acquire high density point cloud data for Germany. The project is run by the *Federal Agency for Cartography and Geodesy* (BKG), Germany's national mapping agency. Data acquisition was supposed to start in 2023 and the goal was to have a data set for entire Germany by 2024. It was also planned to have at least one repition some years later. It was also planned that the data would be mapped by Geiger-Mode or Single Photon Sensor (Leica SPL100) in the vegegtation period [https://doi.org/10.12902/zfv-0379-2021]. It is not planned to make the data available as open source in general, although DTM and DSM mitght be public at 1 meter resolution. Point cloud data might be accessible for scientific research and national authorities only. However, there is also rumors, that at least a downsampled version of point cloud data will be available. 
Currently the initial plans can not be fulfilled anymore and a lot of details about the project are still not organised (see https://fragdenstaat.de/anfrage/informationen-zum-projekt-digitaler-zwilling-deutschland/). 

#### [Digital Twin Germany](https://www.bkg.bund.de/SharedDocs/Pressemitteilungen/BKG/DE/PM_2021/211013-Digitaler_Zwilling.html)

- coordinated by BKG
- data meant for government agencies
- first data collection 2024-2025 
- data collection in the vegetation period
- point density >=40 pts/m²
- case study applied to Hamburg in Winter 2022

### Federal

### [Baden-Württemberg](https://www.lgl-bw.de/Produkte/Geodaten/Laserscandaten/)

- first recording in 2000-2005 (0.8 points per m², €3-80 per km²)
- second recording in 2016-2021 (8 points per m², 10€-80€ per km²)
- as ASCII, LAS or LAZ
- Data from 2016-2022
- 8 points per m²
- DGM1 as ASCII 10€-80€ per km²
- DGM025 as ASCII 20€-160€ per km²
- DOM5 as ASCII (1.875€-15€ per km²)
- bDOM (20cm) asl LAS /LAZ (1,875€-15€ pro km²)
- 1x1km tiles
- EPSG: 25832
- EPSG: 7837
- 5 classes: bridge points, ground points, building points, sub-ground points, vegetation and other non-ground points
- Expected to be open data from 2024


### [Bayern](https://www.ldbv.bayern.de/produkte/3dprodukte/laser.html)

- Data from 2011-2021 as LAS, LAZ, ASCII
- 4 (1) points per m²
- Data available free of charge since 2023
- Point cloud available online from autumn 2023
- DGM1 as GeoTIFF / ASCII
- bDOM (40cm) as LAZ with color values
- 1x1km tiles
- EPSG: 25832
- EPSG: 7837
- nDOM, tDOM and 3D - Mesh in development
- Class: Ground points, object points, unassignable points near the ground, building points

### [Berlin](https://www.stadtentwicklung.berlin.de/geoinformation/landesvermessung/atkis/de/dom.shtml)

- "The data was recorded on three flight days on February 24th, 25th and March 2nd, 2021 with a point density of approximately 10 points per square meter."
- Calculated DGM1/DOM1 downloadable as tiles (2kmx2km)
- Point data can be downloaded as a [Zip](https://fbinter.stadt-berlin.de/fb/berlin/service_intern.jsp?id=a_als@senstadt&type=FEED)
- Classes: Soil (class 2), deep (class 3), medium (class 4) and high vegetation (class 5), outliers (class low points class 7) and default (class 0)
- LAS 1.4 (?) QGIS cannot read
- License https://www.govdata.de/dl-de/by-2-0
- EPSG:25833
- EPSG: 7837
- bDOM1 available based on March 2022 data as XYZ
- DOM1 available based on 2021 data as XYZ


### [Brandenburg](https://geobasis-bb.de/lgb/de/geodaten/3d-produkte/laserscandaten/)

- Data available free of charge since the end of 2021
- current data from 2017, 2018, 2019, 2020, 2021, 2022
- also historical data from 2008 to 2012 (not comprehensive)
- DGM1/bDOM1/ALS
- bDOM from winter flight with poor quality for vegetation
- ALS is not yet widely available
- 5P/m² with current laser scan data
- 1P/m² for historical laser scan data
- downloadable in packages up to a maximum of 200 km² after ordering
- Point cloud (LAS/LAZ 1.4) with current laser scan data
- Point cloud (LAS/LAZ 1.2) on historical laser scan data (2008-2012)
- [Current overview (2018-2012)](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_2008-2012_aktualitaet.pdf) (also as WFS)
- [Current overview (from 2017)](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_aktualitaet.pdf) (also as WFS)
- LAS/LAZ download as individual tiles or as a batch up to a maximum of 200km²
- EPSG:25833
- EPSG: 7837
- License: https://www.govdata.de/dl-de/zero-2-0


### [Bremen](https://www.geo.bremen.de/produkte/3d-produkte/hoehenmodelle-12482)

- DGM1, DOM1 (€80 per km²) as XYZ from 2017/2018
- bDOM (40€ per km²) as GeoTIFF with 5cm from 2021
- ALS data for €80 per km²


### [Hamburg](https://metaver.de/trefferanzeige?docuuid=A39B4E86-15E2-4BF7-BA82-66F9913D5640#detail_overview)

- Data from 2020
- DGM1 can be downloaded free of charge
- EPSG: 25832
- EPSG: 7837
- bDOM1 for 2018 and 2020 as ASCII (via another portal)
- License: https://www.govdata.de/dl-de/zero-2-0


### [Hesse](https://hvbg.hessen.de/landesvermessung/geotopographie/3d-daten/airborne-laserscanning)

- Data 2009 -2020 [current overview](https://gds.hessen.de/INTERSHOP/static/WFS/HLBG-Geodaten-Site/-/HLBG-Geodaten/de_DE/Downloadcenter/Daten/3D-Daten/Aktualit%C3%A4t_3D_0.pdf)
- The second nationwide campaign “Laserscan 2” was completed in 2021
- at least 4 points per m² (first campaign 2009-2014)
- at least 8 points per m² (second campaign 2015-2021)
- 6 year cycle
- DOM1 / DGM1 available as open data (as xyz text file)
- Point clouds up to 1km² can be ordered online, larger areas for a processing fee
- EPSG: 25832
- Open Data since February 1, 2022


### [Mecklenburg Western Pomerania](https://www.laiv-mv.de/Geoinformation/Geobasisdaten/Oberflaechenmodelle/)

- Data from 2012-2022 [current overview](https://www.geoportal-mv.de/dienste/karten_akt_uebersicht_file/Uebersicht_Verfuegbarkeit_ALS-Daten.pdf)
- Point density of 2 (until 2014) - 5 (from 2016) points per m²
- bDOM with 10cm resolution available as LAZ 1.2 (5-20€ per km²)
- DGM1/DOM1 (20 to 80€ per km²)
- Point clouds as LAZ 1.2 (10 to 80€ per km²)
- Classes: ground points, non-ground points? (2,13,15,22,23,25)
- old DOM from 2009-2016?
- Recently, DOM is generated from bDOM
- nDOM1 available
- Test data point cloud with 20 points per m²
- very complicated about application
- EPSG: 25833
- EPSG: 7837


### [Lower Saxony](https://www.lgln.niedersachsen.de/startseite/geodaten_karten/3dgeobasisdaten/3dmessdaten/3d-messdaten-142870.html)

- Data from 2015-2021 [current overview](https://cms.lgln.niedersachsen.de/fb24/dgm1_dom1.pdf)
- DGM “either in ASCII or shape data format”
- not free! (5€ - 40€ per km²)
- DOM as ASCII
- not free! (€2.50 - €20 per km²)
- at least 4 points per m² (apparently refers to ground points?)
- ALS data as LAZ 1.2
- not free! (€3.75 -€30 per km²)
- bDOM present in the test data but not listed
- Point cloud from image data (€2.50-€20 per km²)
- bDOM (2€-16€ pro km²)
- DGM1/DOM1/bDOM possibly open data from 2024
- Classes up to 2020: Ground points (2), outliers (7), water points measured (8), water points synthetic (11), sub-ground points (e.g. entrances/driveways, basement shoots and swimming pools) (12), non-ground points (e.g . B. buildings, vegetation and temporary embankments) (13), other points (DGM and DOM-irrelevant points such as power lines, means of transport, containers and birds) (15), overlap points (20,22,23,25 ,26,27)
- Classes from 2021 (AdV specifications): Ground points (2), outliers (7), measured water points (9), synthetic water points (8), sub-soil points (e.g. entrances/driveways, basement sections and swimming pools) (24), not -Ground points (e.g. buildings, vegetation and temporary embankments) (20), other points (DTM or DOM-irrelevant points such as power lines, means of transport, containers and birds) (1), overlap points (12)
- EPSG: 25832
- EPSG: 7837

### [North Rhine-Westphalia](https://www.bezreg-koeln.nrw.de/geobasis-nrw/produkte-und-dienste/hoehenmodelle/3d-messdaten)

- Data from 2018-2022
- Continuation every 5 years (data collection at the beginning of the year, data availability at the end of the year)
- 4 to 10 points per m²
- "Historical 3DMs can also be submitted upon request."
- Data can be downloaded free of charge
- nDOM 50cm (2017-2021) based on bDOM (and DOM)
- tDOM 50cm based on bDOM
- Continuation overview 2019-2022
- Continuation overview 2023-2027
- ALS data available as preliminary data for rapid deployment
- EPSG: 25832
- EPSG: 7837
- Classes: 1, 2, 9, 17, 18, 20, 21, 24, 26
- License: https://www.govdata.de/dl-de/zero-2-0


### [Rhineland-Palatinate](https://lvermgeo.rlp.de/de/produkte/geotopografie/3d-geodaten/digitale-gelaendemodelle-dgm/)

- at least 4 points per m²
- Point data available as LAZ separated into terrain and object points (€12.50 - €50 per km² each)
- 9-year cycle
- 4-year cycle since 2021
- Data from 2014-2022 [current overview](https://lvermgeo.rlp.de/fileadmin/lvermgeo/pdf/produkte/geotopographie/Uebersicht_Laserbefliegung.pdf)
- not free! (DGM1 20€ -80€ per km²)
- DGM as ASCII, GeoTIFF
- Point data separated into terrain and objects
- currently no DOM from ALS available
- bDOM with 0.5m resolution as an ASCII file (3.75 - 15€ per km²) in a two-year cycle
- EPSG: 25832
- EPSG: 7837

### [Saarland](https://www.shop.lvgl.saarland.de/)

- first ALS flight in 2006 (2-3 points per m²)
- second ALS flight in 2016 (6-8 points per m²)
- Point clouds available with 4 points per m² as LAZ (€120 per km²)
- DOM1 / DGM1 available as XYZ (€80 per km²)
- EPSG: 25832

### [Saxony-Anhalt](https://geodatenportal.sachsen-anhalt.de/gfds/de/gdp-open-data.html)

- ALS data from 2009, 2015, 2017-2023 with (at least) 3-5 points/m² available
- ALS data [current overview](https://www.lvermgeo.sachsen-anhalt.de/datei/anzeigen/id/17602,501/Uebersicht_als.pdf)
- DGM data from 2016-2021 [overview](https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/17600,501/lvermgeo_dgm1_st_aktualitaet_2022_12_01.pdf)
- currently DGM2/DOM2 free of charge
- Point cloud free of charge since 2023
- Point cloud contains RGB values
- From the end of 2023, DGM1/DOM1 may also be free of charge
- DOM1 available as ASCII (cost?)
- bDOM with 0.2m resolution available free of charge as LAZ 1.4, updated every 2 years
- EPSG: 25832
- EPSG: 7837


### [Saxony](https://www.geodaten.sachsen.de/downloadbereich-digitale-hoehenmodelle-4851.html)

- Data from 2015-2022 [current overview](https://www.landesvermessung.sachsen.de/prod_dhm_stadt/dhm_stadt.pdf)
- planned [updates](https://www.landesvermessung.sachsen.de/prod_dhm_stadt/plan_dhm_stadt.pdf)
- Update in a 6-year cycle
- Data can be downloaded free of charge
- 2x2km tiles
- ALS data as (LAS 1.2) LAZ
- at least 4 points per km²
- Classes: 02_ground ground points, 20 non-ground points, 08 interpolated water points, 30 interpolated other
- EPSG: 25833
- EPSG: 7837
- License: https://www.govdata.de/dl-de/zero-2-0


### [Schleswig-Holstein](https://www.schleswig-holstein.de/DE/Landesregierung/LVERMGEOSH/Service/serviceGeobasisdaten/geodatenService_Geobasisdaten_DGM.html)

- currently only [DGM1](https://geodaten.schleswig-holstein.de/gaialight-sh/_apps/dladownload/dl-dgm1.html) from ALS data (3-4 points/m²) available (XYZ in ASCII)
- DGM data largely from 2005-2007
- bDOM with 20cm resolution available (as LAS/LAZ and TIFF)
- bDOM data from 2020-2023
- Open Data since August 1st, 2023 (?)


### [Thuringia](https://www.geoportal-th.de/de-de/Downloadbereiche/Download-Offene-Geodaten-Th%C3%BCringen/Download-H%C3%B6hendaten)

- 4 points per m²
- DGM/DOM/LAZ for the periods 2010-2013, 2014-2019 and 2020-2025 (under construction)
- planned [updates](https://tlbg.thueringen.de/fileadmin/TLBG/Vertrieb/uebersichten/dgm/tlbg-uebersicht-dgm-2020-2025_.pdf)
- DGM1 / DOM1 as ASCII
- Point cloud as LAZ: LAS 1.1 (2010-2013), LAS 1.1 / LAS 1.2 (2014-2019), LAS 1.4 (from 2020)
- 1x1km tiles
- Historical data from 1996 is also available (a total of 3-4 recording times available per location)
- Data can be downloaded free of charge
- EPSG: 25832
- EPSG: 7837