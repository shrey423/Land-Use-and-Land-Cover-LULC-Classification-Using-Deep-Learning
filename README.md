# Land-Use-and-Land-Cover-LULC-Classification-Using-Deep-Learning
This project focuses on Land Use and Land Cover (LULC) classification using satellite imagery and deep learning techniques. It leverages the EuroSAT dataset, a benchmark dataset specifically designed for LULC classification, which consists of Sentinel-2 satellite images covering 10 different land use and land cover classes.
Project Overview

    Objective: Develop a deep learning model using Convolutional Neural Networks (CNNs) to classify satellite images into different land use and land cover categories, such as residential, industrial, agricultural, and forested areas.
    Dataset: The project uses the EuroSAT dataset, which contains Sentinel-2 imagery categorized into 10 classes. This dataset is crucial for various applications such as urban planning, resource management, and environmental monitoring.
    Model: A CNN model has been built and trained to classify the satellite images accurately. The sample model is included in the Model/ directory.

Features

    Deep Learning Framework: Implemented using TensorFlow/Keras.
    Geospatial Analysis: Classification of Sentinel-2 satellite images into distinct land cover categories.
    Transfer Learning: The model can be enhanced using transfer learning to improve accuracy with pre-trained models.
    Real-Time Image Testing: You can test the model's prediction on new satellite images using the provided script.

Usage Instructions

    To Train a New Model:
        Specify the path to the dataset in the Dataset.py file under the variable data_dir.
        Run the classification script: python classify.py.

    To Classify a New Image:
        Update the test image path in the check.py file at line 10: test_path = "path/to/image/image.jpg".
        Run the script to check the classification result: python check.py.

EuroSAT Dataset

The EuroSAT dataset is an open-access benchmark dataset introduced for land use and land cover classification. The dataset includes Sentinel-2 satellite images and covers 10 land use classes such as agricultural land, forests, water bodies, and residential areas.

    Reference Paper:
        Helber, P., Bischke, B., Dengel, A., & Borth, D. (2019). Eurosat: A novel dataset and deep learning benchmark for land use and land cover classification. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing.

Applications

    Urban planning and development
    Environmental monitoring
    Resource management
    Satellite image analysis
