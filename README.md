# Autism-Behavior-Recognition-ML

## Introduction
This project aims to enhance the early diagnosis and intervention of Autism Spectrum Disorder (ASD) by utilizing advanced computer vision models to analyze video recordings of clinical sessions. By automating the detection and classification of problem behaviors, this project seeks to reduce the workload on clinicians and improve the accuracy of behavioral assessments.

## Business Case
Early and accurate recognition of ASD-related behaviors is crucial for timely intervention and treatment. By automating the analysis of clinical session videos, this project aims to reduce the workload of clinicians, improve diagnostic accuracy, and ultimately enhance the quality of care for children with ASD.

## Methodology
- **Dataset**: Collected **15TB data** from the ABA clinic, containing CSV files, image & video recordings of clinical sessions. The dataset includes various ASD-related behaviors like grabbing, head-banging, and aggression.
- **Data Preprocessing**: Utilized FFmpeg for frame extraction and labelimg for manual annotation. Processed and cleaned the data annotations to COCO format to ensure high-quality input formats for the model requirements using Roboflow tool.

- **Models Used**:
Detectron2: A framework for object detection and segmentation.
Video Swin Transformer: A hierarchical vision transformer for action recognition.

## Skills Used
- **Tools**: Python, pytorch, OpenCV, pandas, FFmpeg, labelimg, Roboflow, Detectron2, Video Swin Transformer, SQL
- **Techniques**: Data Preprocessing, Data Annotation, Object Detection, Action Recognition, Model Evaluation

## Conclusion
This project successfully identified and classified ASD-related behaviors with high accuracy of 86.3%, improving data preprocessing and labeling efficiency by 40% and reducing manual data annotation time by 50%. The application of computer vision models like Detectron2 has shown great promise in the early detection and analysis of ASD behaviors, leading to more timely and effective interventions, expanding the dataset for further validation for accurate results to further push it into production.

- Code Repository[]
