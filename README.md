# EYOpenSciData23

The 2023 EY Open Science Data Challenge consisted of two levels - Level 1 and Level 2. 
The Level 1 challenge is aimed at participants who are beginners or have intermediate skills in data science. The goal of Level 1 is to predict the presence, or non-presence, of rice crops at a given location. 
The Level-2 challenge is aimed at participants who are more advanced in data science. The goal of Level 2 is to build a machine learning model that estimates rice crop yield for a given location. Each of these challenges will consider satellite data from the European Copernicus (Sentinel-1 and Sentinel-2) program and from NASA's Landsat program. 

I only attemped the Level 1 challenge.

For the Level-1 challenge, information about the location of rice crops and the locations of non-rice crops (e.g., forest, other vegetation, water) was given. 
By considering time series variations in the satellite data bands and statistical combinations (indices) of those bands, it is possible to identify rice crop locations with fairly high accuracy.

# LSTM Model
Using the TensorFlow2 Package, a simple LSTM model was implemented that could account for trends in Sentinel-1 rvi radar data over a 1-year period.
The model was able to achieve 86% accuracy on the test dataset.
