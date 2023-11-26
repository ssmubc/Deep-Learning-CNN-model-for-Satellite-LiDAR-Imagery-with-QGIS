# Deep-Learning-CNN-model-for-Satellite-LiDAR-Imagery-with-QGIS

Citations:

LiDAR data collected from: 
https://ftp.maps.canada.ca/pub/elevation/dem_mne/highresolution_hauteresolution/dtm_mnt/1m/AB/Edmonton/utm11/?C=M;O=A

I transformed the map, added RGB channels, changed the standard deviation levels, transparency and various other factors using QGIS. I exported the image as a GEOTIF file. I then imported the new map here, and used it to train the CNN model while integrating image patching/tiling.

Studied:
https://www.tensorflow.org/api_docs/python/tf/keras/utils/image_dataset_from_directory
https://www.tensorflow.org/guide/keras/sequential_model 
https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator
