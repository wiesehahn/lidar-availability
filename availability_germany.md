
## Lidar availability - Germany

## National data

According to [Virtanen et al. (2017)](https://doi.org/10.3390/ijgi6080243) "topographic databases maintained by national mapping agencies are currently the most common nationwide data sets in geo-information", however this is not true for Germany. Until now there is no single data set which is available for entire Germany. Instead there are datasets with varying conditions by each federal state. However, there are ongoing efforts to generate such data. The project Digital Twin Germany aims to acquire high density Point Cloud data for Germany. The project is run by the *Federal Agency for Cartography and Geodesy* (BKG), Germany's national mapping agency. Data acquisition was supposed to start in 2023 and the goal was to have a data set for entire Germany by 2024, with at least one repetition some years later. It was also planned that the data would be mapped by Geiger-Mode or Single Photon Sensor (Leica SPL100) in the vegetation period [Hopfstock et al. (2021)](https://doi.org/10.12902/zfv-0379-2021). Current plans are to collect data for all of Germany in the vegetation period in 2024 and 2025. It is expected that the entire dataset is available at the end of 2026, with first data in summer 2025. However, data is primarily meant for national agencies and most likely only a subset will be available as open data. 

### [Digital Twin Germany](https://www.bkg.bund.de/SharedDocs/Pressemitteilungen/BKG/DE/PM_2021/211013-Digitaler_Zwilling.html)

- coordinated by BKG
- data primarily meant for government agencies
- case study applied to Hamburg in Winter 2022 with SPL100 
- data collection 
  - in the vegetation period (March to October)
  - originally planned for 2023-2024 
  - currently planned for 2024-2025 
  - 8 lots flown by different companies (Hexagon, BSF Swissphoto, GEOREAL, FLYCOM) with different sensors (Leica SPL100, Riegl VQ1460, Riegl VQ1560 II-S)
  - collected in 2024: northern  Mecklenburg Western Pomerania, Saxony, North Rhine-Westphalia, Rhineland-Palatinate, western Baden-Württemberg, northeast Bavaria  
  - repetition (3-5 year cycle) is targeted but unclear
- data properties
  -  point density >=40 pts/m²
  -  simultaneous with RGB data
  - classes
    - Building
    - Bridge
    - Water
    - Ground
    - Power lines
    - Low Vegetation
    - Medium Vegetation
    - High Vegetation
    - Objects above ground
    - Low Noise
    - High Noise
    - Unclassified
  - 1.5 PByte data expected
- Derived products
  - Point CLoud with RGB-color (10 points/m²)
  - DTM (50 cm)
  - DSM (25 cm)
  - classified objects (trees, wind turbines, ...)
- Data provision
  - thinned Point CLoud (10 points/m²) available as open data (planned)
  - first data expected in summer 2025 (for national agencies)
  - derived products with delay
  - entire data expected end of 2026

(sources of information: [source1](https://web.archive.org/web/20230401163651/https://www.business-geomatics.com/2022/11/17/zwillinge-gross-gedacht/), [source2](https://www.bkg.bund.de/SharedDocs/Downloads/BKG/DE/Downloads-Forschung/digitaler-zwilling-praesentation.pdf?__blob=publicationFile&v=2), [source3](https://www.bdvi.de/application/files/8716/9565/1129/FORUM_3-2023_Digitaler_Zwilling.pdf), [source4](http://www.eurosdr.net/sites/default/files/images/inline/8-digital_twin_of_germany.pdf), [source5](https://ausschreibungen-deutschland.de/2014266_Befliegung_DigiZDEReferenznummer_der_Bekanntmachung_B_1214_-_090722VV__1_2023_Bonn), [source6](https://wiki.gdi-de.org/x/NwBCTw), [source7](https://fragdenstaat.de/anfrage/informationen-zum-projekt-digitaler-zwilling-deutschland/))

## Federal data

Geodata collection, administration, and distribution in Germany operates primarily through federal structures managed by the land surveying and cadastral authorities of the 16 federal states. While the *Working Committee of the Surveying Authorities of the States of the Federal Republic of Germany* (AdV) establishes guidelines and standards for digital [terrain models](https://www.adv-online.de/AdV-Produkte/Standards-und-Produktblaetter/Standards-der-Geotopographie/binarywriterservlet?imgUid=2b14073e-de6b-1f71-96e7-436303dd7d12&uBasVariant=11111111-1111-1111-1111-111111111111), [surface models](https://www.adv-online.de/AdV-Produkte/Standards-und-Produktblaetter/Standards-der-Geotopographie/binarywriterservlet?imgUid=da14073e-de6b-1f71-96e7-436303dd7d12&uBasVariant=11111111-1111-1111-1111-111111111111), and [Point Clouds](https://www.adv-online.de/AdV-Produkte/Standards-und-Produktblaetter/Standards-der-Geotopographie/binarywriterservlet?imgUid=6b510f6e-a708-d081-505a-20954cd298e1&uBasVariant=11111111-1111-1111-1111-111111111111), the availability and specifications of airborne laser scanning data vary across space and time. For cross-state applications and nationwide analyses, a comprehensive understanding of data availability is essential to ensure efficient project planning and consistent data quality. This compilation of federal ALS data availability draws from state mapping agencies' official websites, direct communication with authorities and additional sources wehere possible.

([source](https://www.adv-online.de/AdV-Produkte/Geotopographie/Digitale-Gelaendemodelle/DGM1/binarywriterservlet?imgUid=7fd603aa-0a3c-a491-d853-6fc506488e77&uBasVariant=11111111-1111-1111-1111-111111111111))

*Comparison of available ALS Point Cloud data in Germany by federal state (the date range refers to the most recent data covering the entire state)*

| Federal State | Cost (min)[^1] | Cost (max)[^2] | Year (from)[^3] | Year (to)[^4] | Point Density[^5] | 
|---|---|---|---|---|---|
| Baden-Württemberg | 10 | 80 | 2016 | 2024 | 8 | 
| Bavaria | 0 | 0 | 2013 | 2024 | 4 | 
| Berlin | 0 | 0 | 2021 | 2021 | 10 | 
| Brandenburg | 0 | 0 | 2017 | 2024 | 5 | 
| Bremen | 80 | 80 | 2017 | 2017 | 7 | 
| Hamburg | - | - | 2022 | 2022 | 15 | 
| Hesse | 0 | 0 | 2016 | 2023 | 8 | 
| Mecklenburg-Western Pomerania | 10 | 80 | 2015 | 2024 | 4-5 | 
| Lower Saxony | 3,75 | 30 | 2015 | 2024 | 4-8 | 
| North Rhine-Westphalia | 0 | 0 | 2019 | 2024 | 4-10 | 
| Rhineland-Palatinate | 0 | 0 | 2019 | 2024 | 4 | 
| Saarland | 0 | 0 | 2015 | 2016 | 8 | 
| Saxony | 0 | 0 | 2016 | 2024 | 4 | 
| Saxony-Anhalt | 0 | 190 | 2009 | 2023 | 3-5 | 
| Schleswig-Holstein | - | - | ? | ? | 3-4 | 
| Thuringia | 0 | 0 | 2019 | 2024 | 4 | 

[^1]: in € per km² (with volume discount; plus processing fee)
[^2]: in € per km² (plus processing fee)
[^3]: oldest data for statewide coverage
[^4]: newsest data for statewide coverage
[^5]: specified minimum number of points/m²


### [Baden-Württemberg](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/)

- two statewide ALS campaigns complete, a the third campaign is ongoing
  - [campaign 1:](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_1/) 0.8 points/m² in 2000-2005 (3-80 €/km², 2/3 classes)
  - [campaign 2:](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_2/) 8 points/m² in 2016-2021 (10-80 €/km², 5 classes)
  - [campaign 3:](https://www.lgl-bw.de/Produkte/3D-Produkte/Laserscandaten/ALS_3/) 8 points/m² in 2022-2029 (10-80 €/km², 7 Classes), ([overview](https://www.geoportal-bw.de/?permalinkId=e042e935-16cf-4497-a3b8-47c3ce477afb#/(sidenav:karten)))
- [DTM025](https://www.lgl-bw.de/Produkte/3D-Produkte/Digitale-Gelaendemodelle/) and [DSM1](https://www.lgl-bw.de/Produkte/3D-Produkte/Digitale-Oberflaechenmodelle/) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2024
- cost of statewide Point Cloud data for one campaign: 720.000 €
- iDSM (20 cm) available as open data (with processing fee)
- no bulk download option

### [Bayern](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)

- ALS data from 1996-2024, rolling data collection
  -  1 points/m² before 2012
  -  4 points/m² since 2012
- 10-year cycle
- [DTM1](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dgm1) and [Point Cloud](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten) available as open data ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)) since 2024
- iDSM (20 cm) as LAZ with color values open data 
- nDOM, tDSM and 3D-Mesh in development
- classes: ground points, object points, unassignable points near the ground, building points

### [Berlin](https://www.stadtentwicklung.berlin.de/geoinformation/landesvermessung/atkis/de/dom.shtml)

- one statewide ALS campaign
  - 10 points/m² in  2021
- DTM1, DSM1 and [Point Cloud](https://fbinter.stadt-berlin.de/fb/berlin/service_intern.jsp?id=a_als@senstadt&type=FEED) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0))
- classes: soil, low vegetation, medium vegetation and high vegetation, outliers and default
- iDSM1 available as open data from march 2022


### [Brandenburg](https://geobasis-bb.de/lgb/de/geodaten/3d-produkte/laserscandaten/)

- one ALS campaign complete, a second campaign is ongoing
  - campaign 1: 1 point/m² in 2008-2012 ([overview](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_2008-2012_aktualitaet.pdf))
  - campaign 2: 5 points/m² in 2017 - ? ([overview](https://data.geobasis-bb.de/geobasis/information/aktualitaeten/bb_laserscandaten_aktualitaet.pdf))
- [DTM1](https://data.geobasis-bb.de/geobasis/daten/dgm/tif/) and [Point Cloud](https://data.geobasis-bb.de/geobasis/daten/als/laz/) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since end of 2021
- not yet entirely covered by ALS data
- [iDSM](https://data.geobasis-bb.de/geobasis/daten/bdom/tif/) (20 cm) available as open data (from winter flight with poor quality for vegetation)


### [Bremen](https://www.geo.bremen.de/produkte/3d-produkte/hoehenmodelle-12482)

- two statewide ALS campaigns complete 
  - campaign 1: in 2012 (Bremen) and 2015 (Bremerhaven)
  - campaign 2: in 2017 (Bremen and Bremerhaven)
- DTM1 and [DSM1](https://metaver.de/trefferanzeige?docuuid=5FDCE552-8111-46D3-9B13-A27A84EC1447&q=laserscanning) available as open data ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)) since 2024
- iDSM (5 cm) from 2021 (40 €/km²)
- [Point Cloud](https://metaver.de/trefferanzeige?docuuid=9AEAE758-FC12-4D9E-AF5E-68537A678588) data for 80 €/km²


### [Hamburg](https://metaver.de/trefferanzeige?docuuid=A39B4E86-15E2-4BF7-BA82-66F9913D5640#detail_overview)

- three statewide ALS campaigns complete 
  - campaign 1: 15 points/m² in 2010
  - campaign 2: 15 points/m² in 2020
  - campaign 3: 15 points/m² in 2022
- [DTM1](https://metaver.de/trefferanzeige?docuuid=A39B4E86-15E2-4BF7-BA82-66F9913D5640#detail_overview) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2024
- Point Cloud not available due to privacy concerns (neither open data nor commercial)
- DSM1 based on ALS data not available (neither open data nor commercial)
- [iDSM1](https://metaver.de/trefferanzeige?docuuid=2AB332A1-B1B6-4706-9546-33F0B1EADB6D&q=dom+hamburg&f=#detail_overview) from 2018 and 2020 available as open data


### [Hesse](https://hvbg.hessen.de/landesvermessung/geotopographie/3d-daten/airborne-laserscanning)

- two statewide ALS campaigns complete, a third campaign is ongoing
  - campaign 1: 4 points/m² in 2009-2014
  - campaign 2: 8 points/m² in 2015-2021
  - campaign 3: 8 points/m² in 2021-2027, ([overview](https://gds.hessen.de/INTERSHOP/static/WFS/HLBG-Geodaten-Site/-/HLBG-Geodaten/de_DE/Downloadcenter/Daten/3D-Daten/Aktualit%C3%A4t_3D_0.pdf))
- 6-year repetition cycle
- DTM1, DSM1 and Point Cloud available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2022


### [Lower Saxony](https://www.lgln.niedersachsen.de/startseite/geodaten_karten/3dgeobasisdaten/3dmessdaten/3d-messdaten-142870.html)

- one statewide ALS campaign complete, a second campaign is ongoing
  - campaign 1: 4 points/m² in 2010-2019 (?)
  - campaign 2: 4-8 points/m² in 2020- (?) ([overview](https://cms.lgln.niedersachsen.de/fb24/dgm1_dom1.pdf))
- 6-year cycle since 2023/2024
- 8 points/m² since 2023/2024
- addition RGBI data since 2023/2024 
- [DTM1](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::digitales-gel%C3%A4ndemodell-dgm1/about) and [DSM1](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::digitales-oberfl%C3%A4chenmodell-dom1/about) available as open data ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)) since 2024 
- Point Cloud data available for 3.75-30 €/km²
- [iDSM](https://ni-lgln-opengeodata.hub.arcgis.com/apps/lgln-opengeodata::bildbasiertes-digitales-oberfl%C3%A4chenmodell-bdom20/about) (20 cm) available as open data


### [Mecklenburg Western Pomerania](https://www.laiv-mv.de/Geoinformation/Geobasisdaten/Oberflaechenmodelle/)

- one statewide ALS campaign complete, a second campaign is ongoing (?)
  - campaign 1: 4-5 points/m² in 2015-2024 ([overview](https://www.geoportal-mv.de/dienste/karten_akt_uebersicht_file/Uebersicht_Verfuegbarkeit_ALS-Daten.pdf))
- [DTM1](https://laiv.geodaten-mv.de/afgvk/Geotopographie/Download?produkt=DGM1) and [DSM1](https://www.laiv-mv.de/Geoinformation/Geobasisdaten/Oberflaechenmodelle/) available as open data ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)) since 2024
- Point Cloud available for 10-80 €/km²
- iDSM (10 cm) available for 5-20 €/km²
- DTM and DSM based on old data, orthophotos are also mentioned as data source


### [North Rhine-Westphalia](https://www.bezreg-koeln.nrw.de/geobasis-nrw/produkte-und-dienste/hoehenmodelle/3d-messdaten)

- statewide ALS campaign complete
  - detailed information about campaigns unavailable
  - approximately 5 campaigns, for sample area in 1997 (~0.1 points/m²), 2008(~3 points/m²), 2013, 2019(4 points/m²), 2022(4 points/m²) 
  - 4-10 points/m²
- [DTM1](https://www.opengeodata.nrw.de/produkte/geobasis/hm/dgm1_tiff/dgm1_tiff/), [DSM1](https://www.opengeodata.nrw.de/produkte/geobasis/hm/dom1_tiff/dom1_tiff/) and [Point Cloud](https://www.opengeodata.nrw.de/produkte/geobasis/hm/3dm_l_las/3dm_l_las/) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2017
- 5-year cycle
- "Historical 3DMs can also be submitted upon request."
- [iDSM](https://www.opengeodata.nrw.de/produkte/geobasis/hm/bdom50_las/bdom50_las/) (50 cm) available as open data 
- ADV-classes: 1,2,9,17,18,20,21,24,26


### [Rhineland-Palatinate](https://lvermgeo.rlp.de/de/produkte/geotopografie/3d-geodaten/digitale-gelaendemodelle-dgm/)

- statewide ALS campaign complete
  - 4 points/m² until 2014
  - 8 points/m² since 2014
  - current data from 2019-2024 ([overview](https://lvermgeo.rlp.de/fileadmin/lvermgeo/pdf/geodaten/Aktualitaet_Laserscanbefliegung.pdf))
- [DTM1](https://geobasis-rlp.de/data/dgm1/) and Point Cloud available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2024
- Point Clouds available separated into terrain (last returns) and object points (first returns) 
- 9-year cycle until 2021
- 4-year cycle since 2022 
- DSM1 based on ALS data not available (neither open data nor commercial) (according to ADV it is available!?)
- iDSM (20 cm) available as open data
- [source](https://lvermgeo.rlp.de/fileadmin/lvermgeo/pdf/produktblaetter/Laserpunkte.pdf)


### [Saarland](https://www.shop.lvgl.saarland.de/)

- two statewide ALS campaigns complete, a third campaign is planned
  - campaign 1:  2-3 points/m² in 2006
  - campaign 2:  8 points/m² in 2015-2016
  - campaign 3: likely in 2025
- [DTM1](https://www.shop.lvgl.saarland.de/index.php?option=com_virtuemart&view=category&virtuemart_category_id=1060&Itemid=156), [DSM1](https://www.shop.lvgl.saarland.de/index.php?option=com_virtuemart&view=category&virtuemart_category_id=1066&Itemid=156) and [Point Cloud](https://www.shop.lvgl.saarland.de/index.php?option=com_virtuemart&view=category&virtuemart_category_id=1067&Itemid=156) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2024
- only thinned Point Cloud available with 4 points/m² and without intensity values
- iDSM (20 cm) available as open data


### [Saxony-Anhalt](https://geodatenportal.sachsen-anhalt.de/gfds/de/gdp-open-data.html)

- one statewide ALS campaign complete, a second campaign is ongoing
  - campaign 1: 4 points/m² in 2009
  - campaign 2: 4 points/m² in 2015-2025 ([overview](https://www.lvermgeo.sachsen-anhalt.de/datei/anzeigen/id/17602,501/Uebersicht_als.pdf))
-  [DTM1](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-dgm-dom-lsa.html) and [Point Cloud](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-klassifizierte-laserscanergebnisse.html) basically available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0)) since 2023
- currently only available for a small region (Halle) through open data platform, other data on request for processing fee of 190€ per dataset plus fee for processing time
- 6-year cycle planned
- DSM1 based on ALS data not available (neither open data nor commercial)
- [iDSM](https://www.lvermgeo.sachsen-anhalt.de/de/gdp-dom-bdom-lsa.html) (20 cm) available as open data, updated every 2 years


### [Saxony](https://www.geodaten.sachsen.de/downloadbereich-digitale-hoehenmodelle-4851.html)

- two statewide ALS campaigns complete, a third campaign is ongoing
  - campaign 1: in 2005-2012 ([overview](https://geoviewer.sachsen.de/mapviewer/resources/apps/bildflug/index.html?lang=de&stateId=18ca179c-8e20-4315-8a17-9c8e2063152d))
  - campaign 2: 4 points/m² in 2015-2020
  - campaign 3: 4 points/m² in 2020-2026
- 6-year cycle since 2020/2021 ([planned overview](https://www.landesvermessung.sachsen.de/prod_dhm_stadt/plan_dhm_stadt.pdf))
- [DTM1, DSM1 and Point Cloud](https://www.landesvermessung.sachsen.de/download-offene-geodaten-und-testdaten-8647.html) available as open data ([dl-by-de/2.0](https://www.govdata.de/dl-de/by-2-0))
- [source](https://www.landesvermessung.sachsen.de/digitale-hoehen-und-stadtmodelle-8641.html)

### [Schleswig-Holstein](https://www.schleswig-holstein.de/DE/Landesregierung/LVERMGEOSH/Service/serviceGeobasisdaten/geodatenService_Geobasisdaten_DGM.html)

- one statewide ALS campaign complete, a second campaign is ongoing
  - campaign 1:  in 2005-2007
  - campaign 2:  4 points/m² in 2021-2026 
- [DTM1](https://geodaten.schleswig-holstein.de/gaialight-sh/_apps/dladownload/dl-dgm1.html) available as open data since 2023
- iDSM (20 cm) available as open data, updated every 2 years
- Point Cloud and DSM1 based on ALS data not available (neither open data nor commercial)
- DSM1 is in preparation


### [Thuringia](https://www.geoportal-th.de/de-de/Downloadbereiche/Download-Offene-Geodaten-Th%C3%BCringen/Download-H%C3%B6hendaten)

- three statewide ALS campaigns complete, a fourth campaign is ongoing
  - campaign 1:  0.05-1.8 points/m² in 1996-2006
  - campaign 2:  4 points/m² in 2010-2013
  - campaign 3:  4 points/m² in 2014-2019 
  - campaign 4:  in 2020-2025, ([overview](https://tlbg.thueringen.de/fileadmin/TLBG/Vertrieb/uebersichten/dgm/tlbg-uebersicht-dgm-2020-2025_.pdf))
- 6-year cycle
- [DTM1, DSM1 and Point Cloud](https://geoportal.thueringen.de/gdi-th/download-offene-geodaten/download-hoehendaten) available as open data since 2017
