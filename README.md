# deep-learning-landcover-classification
# Land Cover Classification of Delhi NCR using Sentinel-2 Satellite Imagery

This project presents a geospatial deep learning pipeline for land cover classification in the Delhi National Capital Region (NCR) using Sentinel-2 satellite imagery and ESA WorldCover land cover data.

The workflow integrates **geospatial data processing and deep learning** to automatically classify satellite image tiles into major land cover categories including built-up areas, cropland, vegetation, water bodies, and other land types.

The study combines vector and raster geospatial data with a convolutional neural network to demonstrate how satellite imagery can be used for automated environmental monitoring and land use analysis.

## Key Features

* Spatial filtering of satellite imagery using Delhi NCR boundary
* Generation of **60 km × 60 km spatial grid**
* Automatic land cover label extraction from **ESA WorldCover raster data**
* Construction of a labeled satellite image dataset
* Deep learning classification using **ResNet-18 (transfer learning)**
* Model evaluation using **Accuracy, F1 Score, and Confusion Matrix**

## Results

* **Model:** ResNet-18 (pretrained)
* **Input Resolution:** 128 × 128 satellite tiles
* **Accuracy:** ~73.5%
* **F1 Score:** ~72%

## Technologies Used

* Python
* PyTorch
* GeoPandas
* Rasterio
* OpenCV
* Scikit-learn
* Matplotlib & Seaborn

## Applications

This approach can support:

* Urban expansion monitoring
* Agricultural land mapping
* Environmental sustainability analysis
* Satellite-based land use planning
