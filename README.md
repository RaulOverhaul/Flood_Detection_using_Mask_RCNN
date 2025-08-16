# Flood_Detection_using_Mask_RCNN

This repository contains the code and resources for a flood detection project that leverages Mask R-CNN to identify and segment flooded areas from satellite and aerial imagery. The project aims to provide an automated, accurate, and scalable solution for rapid flood mapping, which is critical for disaster response and relief efforts.

About the Project

Traditional flood mapping methods can be slow and labor-intensive. This project tackles that challenge by employing a deep learning approach. We use Mask R-CNN, a state-of-the-art instance segmentation model, to precisely outline flooded regions in an image.  The model is trained on a custom dataset of annotated satellite images, learning to distinguish between water and land with high precision.

Features

Automated Flood Detection: Automatically identifies flooded areas from input images.

Instance Segmentation: Provides a pixel-perfect mask of each flooded region, not just a bounding box.

High Accuracy: The Mask R-CNN model is fine-tuned to achieve high accuracy in detecting various flood conditions.

Scalable Solution: Can be deployed for large-scale, real-time flood monitoring.

Custom Dataset: Trained on a specially curated dataset to handle diverse environmental conditions.

