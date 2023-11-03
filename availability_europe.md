
## Lidar availability - Europe

As of 2021 a total of 18 from 32 countries (EU27, Norway, Switzerland, UK, Serbia) are fully covered by LiDAR data. 

Most European countries provide ALS data free of charge, an overview can be seen as a table in a recent publication by https://doi.org/10.1111/ddi.13644. Another more detailed but also slightly older overview about lidar data availability in Europe was produced by the JRC [https://doi.org/10.2760/212427].

### [Belgium](https://remotesensing.vlaanderen.be/apps/openlidar/#collapseDataDownload)
- Lidar 1 collected 2001-2004 (0.25 Points per m²)
- Lidar 2 collected 2013-2015 (8 Points per m² per strip, effectively 16 pts/m²) together with RGB images (10cm)
- during the winter flying season (November 15 to April 15)
- classification into ground level, non-ground level and water
- LAZ, DTM025, DSM1, flow accumulation, hillshade, skyview factor, solar irradiance

### Czech Republic
- Open Data since 2023 ([Open Data Announcment](https://t.co/hL7nHeL0hk))

### [Denmark](https://dataforsyningen.dk/data/3931)
- Open Data since 2013 ([source](https://groups.google.com/g/lastools/c/m2OKr241LOo))
- average density of 4-5 points/m2 for data collected in 2014/15 and 8 points/m2 for data from 2018 onwards
- updated, approx. 1/5 per year
- 13 classifications, which include terrain, building, vegetation and bridge points
- DTM04/ DSM04/Pointcloud/... (login required)

### [England](https://environment.data.gov.uk/dataset/2e8d0733-4f43-48b4-9e51-631c25d1b0a9)
- Open Data since 2015 ([source](https://environment.data.gov.uk/dataset/2e8d0733-4f43-48b4-9e51-631c25d1b0a9))
- DSM/DTM/Pointcloud
- First data from 2006
- 5km² tiles
- LAZ 
- latest data from 2016-2021
- during winter months (approximately November to April each year)
- classified into ground, low, medium and high vegetation

### [Estonia](https://geoportaal.maaamet.ee/eng/Spatial-Data/Geo3D/3D-Data-p836.html)
- countrywide coverage
- DSM/DTM/CHM  (1m GeoTIFF)
- Pointcloud (LAZ 1.4)
- 1km² tiles
- 2008-2011, 2012-2015, 2017-2020, 2021-

### [Finland](https://www.maanmittauslaitos.fi/en/maps-and-spatial-data/expert-users/product-descriptions/laser-scanning-data-5-p)
- Open Data (since at least 2017)
- Pointcloud (0.5 points per m², LAZ 1.2)
- updated annually ([map](https://tilannekartta.maanmittauslaitos.fi/laserkeilaus))
- 2008-2019, 2020-
- Pointcloud produced with5 >5 points per m², reduced version (0.5) is open data

### [France](https://geoservices.ign.fr/lidarhd)
- (raw and classified point clouds, derived products) is disseminated in open data 
- assessment ongoing (2021 - 2026)
- minimum density of 10pts/m²
- A distribution of derivative products with a resolution of 50 cm is under consideration.
  
Minimum density of 10pts/m² (density not guaranteed above 2500m altitude)
Details:
Height: 10 cm
Planimetric: 50 cm o
Classification (11 classes)
Floor
Low vegetation (from 0 to 50 cm in height)
Average vegetation (from 50 cm to 1.50 m in height)
Tall vegetation (> 1.50 m high)
Buildings
Water
Bridge
Perennial sursol (which includes all artificial installations outside buildings, such as wind turbines, antennas, catenaries, etc.)
Artifact (obviously false point of the cloud, not corresponding to a reality on the ground)
Virtual point (artificial point created under the bridges in order to remove them in the digital models)
Unclassified (moving object like a vehicle, and other item that is not part of other classes)
- Raster derived products (digital models) in .asc format:

Resolution :
5m
1m
A resolution of 50 cm is tested to know if it is relevant to keep it in time.
Digital terrain model (or DEM)
Digital surface model (or DSM)
Digital Height Model (or DHM). The MNH by definition removes the altitude of the MNS and keeps only the above ground elements (buildings, vegetation...).
- Vector quality masks


### [Luxembourg](https://lidar.geoportail.lu/)
- obtained in 2019
- 15 Points per m²
- [about the data](https://data.public.lu/en/datasets/lidar-2019-releve-3d-du-territoire-luxembourgeois/)

### [Netherlands](https://www.ahn.nl/)
- Open Data (since at least 2017)
- [Dataset: Actueel Hoogtebestand Nederland (AHN3)](https://www.pdok.nl/introductie/-/article/actueel-hoogtebestand-nederland-ahn3-)
- [AHN4](https://www.ahn.nl/_flysystem/media/ahn4_in_drie_jaar._en_daarna_-_jeroen_leusink_hwh.pdf)
- 4 nationwide campaigns (5th is starting 2023)
- currently 3 years to cover country
- currently 10-15 points/m²
- point cloud from image matching yearly since 2018
- more information in this [presentation](https://www.ahn.nl/_flysystem/media/ahn4_in_drie_jaar._en_daarna_-_jeroen_leusink_hwh.pdf) 

### [Norway](https://hoydedata.no/LaserInnsyn2/)
### [Poland](https://mapy.geoportal.gov.pl/imap/Imgp_2.html)
https://geoportal.gov.pl/en/dane/dane-pomiarowe-lidar
- Open Data (DSM/DTM/Pointcloud)
- interactive Point viewer
- DTM1 / DSM0.5
- 4-12 points/m²
- 
### [Scotland](https://remotesensingdata.gov.scot/data#/list)
- Open Data
- considers annual laser scan ([The Guardian](https://www.theguardian.com/environment/2023/may/12/scotland-annual-laser-scan-monitor-forest-health-aoe), 12.05.2023)
- around 40% of the country available by 2021 ([source](https://maps.nls.uk/guides/lidar/index.html))
- 2009, 2017-2019, 2021-2022 (no national coverage)

### [Slovakia](https://www.geoportal.sk/en/zbgis/als/)
- Open Data (DSM1, DTM1, PointCloud)
- 2017-2023 (>5 pulses per m²)
- 2022-2026 (>15 pulses per m²)

### [Slovenia]
- Open Data (since at least 2017)

### [Spain]()
- Open Data (since at least 2017)
 
### [Switzerland](https://www.swisstopo.admin.ch/en/geodata/height/surface3d.html#download)
- 6 years update cycle
- LAS 1.2 : free download
- Minimum 5 pts/m2, mean around 15-20 pts/m2
- complete acquisition in 2023 finished
- no update of swissSURFACE3D is planned

### [Wales](https://datamap.gov.wales/maps/lidar-viewer/)
- Open Data since 2015
- latest Data from 2020-2022
- 25cm, 50cm, 1m DTM and DSM