Solar Panel Anomaly Detection Using YOLOv8

This project presents a deep learning–based anomaly detection system for photovoltaic (PV) solar panels. The system leverages computer vision techniques implemented with OpenCV and state-of-the-art object detection models from the YOLO family.

Extensive experimental evaluations were conducted using multiple YOLO architectures. Based on comparative performance analysis in terms of precision, recall, mAP, and inference speed, YOLOv8—developed by Ultralytics—was selected as the optimal model.

The final model was trained on a dataset containing more than 10,000 annotated samples.

System Capabilities

Deep learning–based anomaly detection in PV panels

YOLOv8 model training and optimization

Support for dynamic .pt model loading

Automated inference pipeline

Metadata extraction (EXIF-based GPS parsing)

Geospatial visualization via Google Maps integration

Automated report generation

Output packaging in compressed .zip format

Methodology

Dataset preparation and annotation (10,000+ labeled images)

Model training and hyperparameter optimization

Performance evaluation and model selection

Deployment-ready inference system

GPS metadata extraction from input images

Automated anomaly localization on map interface

This system provides a scalable and deployable framework for intelligent solar panel monitoring and fault diagnostics.
