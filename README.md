# SB_STRS
## Special Topics in Remote Sensing
### Unsupervised Classification of Erdek
#### Personal Homework
##### Semih Bulut

- Within the scope of the project in which Erdek Island and its surroundings were classified, application was made with python code using Google Earth Engine API.
- Using Jupyter Notebook, during operations with Python codes; "geemap", "ee" and "os" libraries and "earthengine api" are used.
- The classification made is "unsupervised classification" and "K-Means" method has been used.
-In the study carried out with Landsat-08 images, the cleanest image was obtained with the help of the codes written during the period between 01.01.2018 and 31.12.2019. The image used is the LANDSAT-08 image of 03.07.2018. The cloudiness ratio of the image is 0.02.
-The image is classified over the combination of "B4", "B3", "B2" bands.
-During the analysis process, analysis was made on 4 clusters. The classes analyzed from the image are "Forest", "Artificial", "Agricultural" and "Water" areas.
-The cluster image obtained was exported using the "os" library.
-The features of the satellite image obtained using the Google Earth Engine API are as follows:
 - CLOUD_COVER: 0.02
 - CLOUD_COVER_LAND: 0.01
 - EARTH_SUN_DISTANCE: 1.016671
 - ESPA_VERSION: 2_23_0_1a
 - GEOMETRIC_RMSE_MODEL: 6.812
 - GEOMETRIC_RMSE_MODEL_X: 4.902
 - GEOMETRIC_RMSE_MODEL_Y: 4.731
 - IMAGE_DATE: 2018-07-03
 - IMAGE_QUALITY_OLI: 9
 - IMAGE_QUALITY_TIRS: 9
 - LANDSAT_ID: LC08_L1TP_181032_20180703_20180717_01_T1
 - LEVEL1_PRODUCTION_DATE: 1531790086000
 - NOMINAL_SCALE: 30
 - PIXEL_QA_VERSION: generate_pixel_qa_1.6.0
 - SATELLITE: LANDSAT_8
 - SENSING_TIME: 2018-07-03T08:51:03.0197999Z
 - SOLAR_AZIMUTH_ANGLE: 127.869438,
 - SOLAR_ZENITH_ANGLE: 24.914536
 - SR_APP_VERSION: LaSRC_1.3.0
 - WRS_PATH: 181
 - WRS_ROW: 32
 - system:asset_size: '581.571197 MB
 - system:band_names: ['B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7']
 - system:id: 'LANDSAT/LC08/C01/T1_SR/LC08_181032_20180703
 - system:index: 'LC08_181032_20180703
 - system:time_end: '2018-07-03 08:51:03
 - system:time_start: '2018-07-03 08:51:03
 - system:version: 1532420079156771
 
 
