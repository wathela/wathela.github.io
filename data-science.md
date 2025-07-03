---
layout: default
title: "Data Science"
permalink: /data-science/
---



<div id="data-science" class="tab-content"> 
    <h2>Data Science Projects</h2>

    <!-- Building Damage Assessment using Sentinel-1-->
    <div id="builiding-damage-S1">

    <h3>Building Damage Assessment in Khartoum using Sentinel-1 Data</h3>
    <h4>Description:</h4>
    Sentinel-1 (IW mode) captures radar images that reveal surface changes under all weather and lighting conditions.
    By comparing pre- and post-conflict images, changes in radar backscatter highlight structural damage.
    Damaged buildings show distinct signal changes due to collapse, debris, or fire.
    In this project, Sentinel-1 images from before and after the ongoing April 14 conflict were used to detect building damage in Khartoum. Open-source building footprints from Overture Maps were used to localize damage at the building level.
    The map below visualizes detected damage, with a focus on the Soba Industrial Area.

    <p align="center">
            <img src="../assets/images/map.png" width="700px">
    </p>

    <h4>Tools:</h4>
    <li><strong> Google Earth Engine (SAR processing, change detection) </li>
    <li><strong> Geemap (interactive mapping & visualization) </li>
    <li><strong> Rasterio and Rasterstats (spatial statistics) </li>
    <li><strong> Overture Maps (open building footprint data)</li>


    </div>



    <!-- Crop Classification of Belle-Île Island using Sentinel-1 and Sentinel-2 Data -->
    <div id="crop-classification-belle-ile">
    <h3>Crop Classification of Belle-Île Island using Sentinel-1 and Sentinel-2 Data</h3>
    <h4>Description:</h4>
    <p>In this project, I used vegetation indices derived from both Sentinel-1 and Sentinel-2 imagery for the crop classification of Belle-Île Island, France. This end-to-end project demonstrates the complete workflow, including data acquisition, preprocessing, feature engineering, and modeling.</p>
    <h4>Key Features and Tools:</h4>
    <ul>
        <li><strong>Data Acquisition and Processing:</strong> Leveraged the Google Earth Engine (GEE) Python API for querying and processing satellite imagery.</li>
        <li><strong>Feature Engineering:</strong>
            <ul>
                <li><strong>Sentinel-2 Vegetation Indices:</strong> NDVI, GNDVI, NBR, and EVI.</li>
                <li><strong>Sentinel-1 Indices:</strong> RVI, DPSVI, and DPSVIo.</li>
            </ul>
        </li>
        <li><strong>Modeling:</strong> Implemented crop classification using <strong>Random Forest</strong> and <strong>XGBoost</strong> machine learning algorithms.</li>
        <li><strong>Visualization:</strong> Utilized <strong>geemap</strong> for interactive visualizations.</li>
    </ul>
    <h4>Full Implementation:</h4>
    <p>For the full implementation and detailed steps, please visit the <a href="https://github.com/wathela/Sentinel1-2CropML-Classification">GitHub repository</a>.</p>
    </div>

    <!-- Rain Prediction Using Machine Learning Models -->
    <div id="rain-prediction-ml-project">
     <h4>-----------------------------------------------------------------------------------------------------------------------------------------------------</h4>
    <h4></h4>
    <h3>Rain Prediction Using Machine Learning Models</h3>
    <h4>Project Description:</h4>
    <p>This project aims to predict the likelihood of rain using weather tabular data. Several machine learning algorithms were implemented, including:</p>
    <ul>
        <li><strong>K-Nearest Neighbors (KNN)</strong></li>
        <li><strong>Random Forest</strong></li>
        <li><strong>Decision Tree</strong></li>
        <li><strong>Naive Bayes</strong></li>
        <li><strong>Support Vector Machine (SVM)</strong></li>
        <li><strong>Multi-Layer Perceptron (MLP)</strong></li>
    </ul>
    <h4>Workflow:</h4>
    <ul>
        <li><strong>Data Exploration and Cleaning:</strong> Conducted analysis and preprocessing to handle missing values and outliers.</li>
        <li><strong>Data Pipeline Construction:</strong> Built a pipeline with data imputation and categorical encoding to prepare data for model training.</li>
        <li><strong>Model Training:</strong> Trained multiple machine learning models to compare performance.</li>
        <li><strong>Cross-Validation:</strong> Applied cross-validation to select the best-performing model.</li>
        <li><strong>Hyperparameter Tuning:</strong> Used grid search with cross-validation to fine-tune model parameters for optimal accuracy.</li>
    </ul>
    <p>This project showcases an end-to-end machine learning workflow for weather prediction, emphasizing model evaluation and efficient data handling techniques.</p> 
    <p>Full implementation available on <a href="https://github.com/wathela/WeatherPredict">GitHub</a>.</p>
    <!-- <div align="center">
        <img src="../assets/images/weather_project.png" alt="Project Image" width="600px">
    </div> -->
    </div>

   

    <!-- Sentinel-2 Image Clustering -->
    <div id="s2-clustering">
        <h4>-----------------------------------------------------------------------------------------------------------------------------------------------------</h4>
        <h4></h4>
        <h3>Sentinel-2 Image Clustering in Python</h3>
        <h4>Description:</h4>  
        <p>Using Sentinel-2 satellite imagery, in this project I demonstrate how to use machine learning clustering techniques to classify various land cover types. Using Python libraries and Sentinel-2 satellite imagery in Algezeria state, Sudan. Clustering segments satellite images into meaningful groups based on spectral information. This approach helps in analyzing environmental and land-use patterns and supports decision-making in agriculture, urban planning, and conservation.</p>
        <h4>Highlights:</h4>
        <ul>
            <li><strong>Utilized Sentinel-2 images for unsupervised clustering.</strong></li>
            <li><strong>Explored K-means clustering algorithm.</strong></li>
            <li><strong>Python libraries: rasterio, scikit-learn, numpy, matplotlib</strong></li>
            <li><strong>Read more:</strong>: <a href="https://towardsdatascience.com/sentinel-2-image-clustering-in-python-58f7f2c8a7f6">Towards Data Science Article</a> and check the vailable code on <a href="https://github.com/wathela/Sentinel2-clustering">GitHub</a>.</li>
        </ul>
    </div>
</div>