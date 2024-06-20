
## Lidar availability - Germany

Geodata collection, administration and publication in Germany is predominantly organized in federal structures by the land surveying and cadaster authorities of the 16 federal states. Although the *Working Committee of the surveying authorities of the states of the Federal Republic of Germany* (AdV) defines guidelines and standards there is still a variety of different data types in the realm of laser scanning data. For applications on a broader scal, beyond state boundaries, it is essential to know the data availability. Hence, information on federal ALS was collected from federal mapping agencies' websites and other sources such as personal and Email comunication.


*Comparison of available ALS data in Germany by state (in case multiple campaigns are available the date range refers to the last finished campaign)*

| Federal State | Cost (min)[^1] | Cost (max)[^2] | Year (from)[^3] | Year (to)[^4] | Point Density[^5] | Format | CRS (EPSG) |
|---|---|---|---|---|---|---|---|
| Baden-Württemberg | 10 | 80 | 2016 | 2021 | 8 | LAZ 1.2 | 25832 |
| Bavaria | 0 | 0 | 2011 | 2021 | 4 | LAZ 1.2 | 25832 |
| Berlin | 0 | 0 | 2021 | 2021 | 10 | LAS 1.4 | 25833 |
| Brandenburg | 0 | 0 | 2017 | 2022 | 5 | LAZ 1.4 | 25833 |
| Bremen | 80 | 80 | 2017 | 2017 | ? | ? | 25832 |
| Hamburg | ? | ? | 2020 | 2020 | ? | ? | 25832 |
| Hesse | 0 | 0 | 2009 | 2020 | 4 | LAS 1.3 | 25832 |
| Mecklenburg-Western Pomerania | 10 | 80 | 2012 | 2022 | 2-5 | LAZ 1.2 | 25833 |
| Lower Saxony | 3,75 | 30 | 2015 | 2022 | 4 | LAZ 1.2 | 25832 |
| North Rhine-Westphalia | 0 | 0 | 2018 | 2023 | 4-10 | LAZ 1.2 | 25832 |
| Rhineland-Palatinate | 0 | 0 | 2018 | 2023 | 4 | LAZ 1.2 | 25832 |
| Saarland | 120 | 120 | 2016 | 2016 | 4 | LAS 1.2 | 25832 |
| Saxony | 0 | 0 | 2015 | 2023 | 4 | LAZ 1.2 | 25833 |
| Saxony-Anhalt | 0 | 0 | 2009 | 2023 | 3-5 | LAZ 1.2 | 25832 |
| Schleswig-Holstein | ? | ? | ? | ? | 3-5 | ? | 25832 |
| Thuringia | 0 | 0 | 2017 | 2023 | 4 | LAZ 1.4 | 25832 |

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

### [Baden-Württemberg](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/)

- [DGM025](https://www.lgl-bw.de/Produkte/3D-Produkte/Digitale-Gelaendemodelle/) and [DOM1](https://www.lgl-bw.de/Produkte/3D-Produkte/Digitale-Oberflaechenmodelle/) available as open data since 2024
- there are two statewide laserscanning campaigns available and the third is ongoing
  - [ALS_1](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_1/) in 2000-2005 (0.8 points per m², €3-80 per km², 2/3 classes)
  - [ALS_2](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_2/) in 2016-2021 (8 points per m², 10€-80€ per km², 5 classes)
  - [ALS_3](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_3/) in 2022-2029 (8 points per m², 10€-80€ per km², 7 Classes), [current state](https://www.geoportal-bw.de/?permalinkId=e042e935-16cf-4497-a3b8-47c3ce477afb#/(sidenav:karten))
- as ASCII, LAS or LAZ
- statewide ALS data of one campaign for 720.000€
- DGM1 available from first cammpaign
- DGM025 available from second campaign
- DOM5 available from first cammpaign
- DOM1 available from second campaign
- bDOM02 (20cm) as LAS/LAZ open data with processing fee

(no bulk download option)

### [Bayern](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)

- [DGM1](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dgm1) and [pointcloud](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten) open data since 2024 (?)
- Data from 2011-2021 as LAS, LAZ, ASCII
- 4 points per m²
- 1x1 km tiles
- bDOM (40cm) as LAZ with color values open data 
- nDOM, tDOM and 3D-Mesh in development
- classes: Ground points, object points, unassignable points near the ground, building points

### [Berlin](https://www.stadtentwicklung.berlin.de/geoinformation/landesvermessung/atkis/de/dom.shtml)
- DGM1, DOM1 and [pointcloud](https://fbinter.stadt-berlin.de/fb/berlin/service_intern.jsp?id=a_als@senstadt&type=FEED) available as open data 
- "The data was recorded on three flight days on February 24th, 25th and March 2nd, 2021 with a point density of approximately 10 points per square meter."
- Classes: Soil (class 2), deep (class 3), medium (class 4) and high vegetation (class 5), outliers (class low points class 7) and default (class 0)
- LAS 1.4 (?) QGIS cannot read
- EPSG:25833
- bDOM1 available based on March 2022 data as XYZ
- DOM1 available based on 2021 data as XYZ


### [Brandenburg](https://geobasis-bb.de/lgb/de/geodaten/3d-produkte/laserscandaten/)

- [DGM1](https://data.geobasis-bb.de/geobasis/daten/dgm/tif/), [bDOM1](https://data.geobasis-bb.de/geobasis/daten/bdom/tif/) and [pointcloud](https://data.geobasis-bb.de/geobasis/daten/als/laz/) available as open data since end of 2021
- current data from 2017-2023 (not yet comprehensive)
- historical data from 2008 to 2012 (not comprehensive)
- bDOM from winter flight with poor quality for vegetation
- 5P/m² with current laser scan data
- 1P/m² for historical laser scan data
- Point cloud (LAS/LAZ 1.4) with current laser scan data
- Point cloud (LAS/LAZ 1.2) on historical laser scan data (2008-2012)
- [Current overview (2018-2012)](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_2008-2012_aktualitaet.pdf)
- [Current overview (from 2017)](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_aktualitaet.pdf)
- EPSG:25833


### [Bremen](https://www.geo.bremen.de/produkte/3d-produkte/hoehenmodelle-12482)

- DGM1 and [DOM1](https://metaver.de/trefferanzeige?docuuid=5FDCE552-8111-46D3-9B13-A27A84EC1447&q=laserscanning) open data since 2024
- data from 2015 (Bremerhaven) and 2017 (Bremen)
- bDOM (40€ per km²) as GeoTIFF with 5cm from 2021
- ALS data for €80 per km²


### [Hamburg](https://metaver.de/trefferanzeige?docuuid=A39B4E86-15E2-4BF7-BA82-66F9913D5640#detail_overview)

- [DGM1](https://metaver.de/trefferanzeige?docuuid=A39B4E86-15E2-4BF7-BA82-66F9913D5640#detail_overview) available as open data since 2024
- data from 2010, 2020 and 2022
- [bDOM1](https://metaver.de/trefferanzeige?docuuid=2AB332A1-B1B6-4706-9546-33F0B1EADB6D&q=dom+hamburg&f=#detail_overview) for 2018 and 2020 as ASCII


### [Hesse](https://hvbg.hessen.de/landesvermessung/geotopographie/3d-daten/airborne-laserscanning)

- DGM1, DOM1 and pointcloud available as open data since 2022
- there are two statewide laserscanning campaigns complete and the third is ongoing (6 year repition cycle)
  - ALS_1 in 2009-2014 (4 points per m²)
  - ALS_2 in 2015-2021 (8 points per m²)
  - ALS_3 in 2022-2028, [current state](https://gds.hessen.de/INTERSHOP/static/WFS/HLBG-Geodaten-Site/-/HLBG-Geodaten/de_DE/Downloadcenter/Daten/3D-Daten/Aktualit%C3%A4t_3D_0.pdf)

### [Mecklenburg Western Pomerania](https://www.laiv-mv.de/Geoinformation/Geobasisdaten/Oberflaechenmodelle/)

- [DGM1](https://laiv.geodaten-mv.de/afgvk/Geotopographie/Download?produkt=DGM1) and [DOM1](https://www.laiv-mv.de/Geoinformation/Geobasisdaten/Oberflaechenmodelle/) available as open data since 2024
- current data from 2012-2022 [current state](https://www.geoportal-mv.de/dienste/karten_akt_uebersicht_file/Uebersicht_Verfuegbarkeit_ALS-Daten.pdf)
- point density 2 (until 2014) - 5 (from 2016) points per m²
- bDOM with 10cm resolution available as LAZ 1.2 (5-20€ per km²)
- DGM1/DOM1 (20 to 80€ per km²)
- pointclouds as LAZ 1.2 (10 to 80€ per km²)
- classes: ground points, non-ground points? (2,13,15,22,23,25)
- DGM and DOM based on old data, as data source orthophotos are also mentioned
- test data pointcloud with 20 points per m²
- EPSG: 25833


### [Lower Saxony](https://www.lgln.niedersachsen.de/startseite/geodaten_karten/3dgeobasisdaten/3dmessdaten/3d-messdaten-142870.html)

- [DGM1](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::digitales-gel%C3%A4ndemodell-dgm1/about) and [DOM1](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::digitales-oberfl%C3%A4chenmodell-dom1/about) available as open data since 2024 
- current data from 2013-2022 [current state](https://cms.lgln.niedersachsen.de/fb24/dgm1_dom1.pdf)
- point density 4 points per m²
- ALS data as LAZ 1.2 (€3.75 -€30 per km²)
- [bDOM](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::bildbasiertes-digitales-oberfl%C3%A4chenmodell-bdom20/about) (20cm) available as open data
- classes up to 2020: Ground points (2), outliers (7), water points measured (8), water points synthetic (11), sub-ground points (e.g. entrances/driveways, basement shoots and swimming pools) (12), non-ground points (e.g . B. buildings, vegetation and temporary embankments) (13), other points (DGM and DOM-irrelevant points such as power lines, means of transport, containers and birds) (15), overlap points (20,22,23,25 ,26,27)
- classes from 2021 (AdV specifications): Ground points (2), outliers (7), measured water points (9), synthetic water points (8), sub-soil points (e.g. entrances/driveways, basement sections and swimming pools) (24), not -Ground points (e.g. buildings, vegetation and temporary embankments) (20), other points (DTM or DOM-irrelevant points such as power lines, means of transport, containers and birds) (1), overlap points (12)

### [North Rhine-Westphalia](https://www.bezreg-koeln.nrw.de/geobasis-nrw/produkte-und-dienste/hoehenmodelle/3d-messdaten)

- [DGM1](https://www.opengeodata.nrw.de/produkte/geobasis/hm/dgm1_tiff/dgm1_tiff/), [DOM1](https://www.opengeodata.nrw.de/produkte/geobasis/hm/dom1_tiff/dom1_tiff/) and [pointcloud](https://www.opengeodata.nrw.de/produkte/geobasis/hm/3dm_l_las/3dm_l_las/) available as open data 
- current data from 2018-2023 (5 year repition cycle)
- point density 4 to 10 points per m²
- "Historical 3DMs can also be submitted upon request."
- [bDOM](https://www.opengeodata.nrw.de/produkte/geobasis/hm/bdom50_las/bdom50_las/) (50cm) 
- classes: 1,2,14,17,18,20,24,26


### [Rhineland-Palatinate](https://lvermgeo.rlp.de/de/produkte/geotopografie/3d-geodaten/digitale-gelaendemodelle-dgm/)

- [DGM1](https://geobasis-rlp.de/data/dgm1/) and pointcloud available as open data since 2024
- at least 4 points per m²
- point data available as LAZ separated into terrain (last returns) and object points (first returns) 
- 9-year cycle
- 4-year cycle since 2021
- current data from 2018-2023 [current state](https://lvermgeo.rlp.de/fileadmin/lvermgeo/pdf/geodaten/Aktualitaet_Laserscanbefliegung.pdf)
- currently no DOM from ALS available
- bDOM (20cm) available as open data


### [Saarland](https://www.shop.lvgl.saarland.de/)

- ALS_1 in 2006 (2-3 points per m²)
- ALS_2 in 2016 (6-8 points per m²)
- Point clouds available with 4 points per m² as LAZ (€120 per km²)
- DOM1 / DGM1 available as XYZ (€80 per km²)

### [Saxony-Anhalt](https://geodatenportal.sachsen-anhalt.de/gfds/de/gdp-open-data.html)

- [DGM2](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-dgm-dom-lsa.html), [DOM2](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-dom-bdom-lsa.html) and [pointcloud](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-klassifizierte-laserscanergebnisse.html) available as open data since 2023
- ALS data from 2009, 2015, 2017-2023 with (at least) 3-5 points/m² available [current state](https://www.lvermgeo.sachsen-anhalt.de/datei/anzeigen/id/17602,501/Uebersicht_als.pdf)
- DGM from 2021-2023 (?) [current state](https://www.lvermgeo.sachsen-anhalt.de/de/datei/download/id/17600,501/lvermgeo_dgm1_st_aktualitaet_2023_12_01_2x2km.pdf)
- bDOM (20cm) available as open data, updated every 2 years


### [Saxony](https://www.geodaten.sachsen.de/downloadbereich-digitale-hoehenmodelle-4851.html)

- [DGM1, DOM1 and pointcloud](https://www.landesvermessung.sachsen.de/download-offene-geodaten-und-testdaten-8647.html) availabe as open data
- Data from 2015-2023 [current state](https://www.landesvermessung.sachsen.de/prod_dhm_stadt/dhm_stadt.pdf)
- planned [updates](https://www.landesvermessung.sachsen.de/prod_dhm_stadt/plan_dhm_stadt.pdf)
- Update in a 6-year cycle
- point density 4 points per m²
- classes: 02 ground ground points, 20 non-ground points, 08 interpolated water points, 30 interpolated other
- EPSG: 25833


### [Schleswig-Holstein](https://www.schleswig-holstein.de/DE/Landesregierung/LVERMGEOSH/Service/serviceGeobasisdaten/geodatenService_Geobasisdaten_DGM.html)

- [DGM1](https://geodaten.schleswig-holstein.de/gaialight-sh/_apps/dladownload/dl-dgm1.html) available as open data since 2023
- point density 3-4 points per m² available (XYZ in ASCII)
- DGM data largely from 2005-2007
- bDOM with 20cm resolution available as open data


### [Thuringia](https://www.geoportal-th.de/de-de/Downloadbereiche/Download-Offene-Geodaten-Th%C3%BCringen/Download-H%C3%B6hendaten)

- [DGM1, DOM1 and pointcloud](https://geoportal.thueringen.de/gdi-th/download-offene-geodaten/download-hoehendaten) available as open data since 2017
- there are two statewide laserscanning campaigns complete and the third is ongoing
  - ALS_1 in 2010-2013
  - ALS_2 in 2014-2019 
  - ALS_3 in 2014-2019, [current state](https://tlbg.thueringen.de/fileadmin/TLBG/Vertrieb/uebersichten/dgm/tlbg-uebersicht-dgm-2020-2025_.pdf)
- 4 points per m²
- historical data from 1996 is also available in parts