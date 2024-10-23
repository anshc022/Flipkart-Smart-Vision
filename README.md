# Smart Vision System for Automated Quality Control

## Abstract
The **Smart Vision System for Automated Quality Control** is a cutting-edge solution developed to address the growing need for efficiency and accuracy in product inspections within the e-commerce sector. Utilizing state-of-the-art technologies like YOLO (You Only Look Once), Convolutional Neural Networks (CNNs), Support Vector Machines (SVMs), and Optical Character Recognition (OCR), this system automates the evaluation of product quality, freshness, and packaging conditions. By integrating real-time data processing with advanced machine learning techniques, the system aims to enhance operational efficiency, reduce errors, and ensure high-quality standards in product deliveries.

## Overview
This project aims to implement a robust quality control system that leverages image processing and machine learning to automate the inspection of products on a conveyor belt. The system captures high-resolution images of products, analyzes them for quality and freshness, extracts relevant information from labels, and updates a central database for real-time inventory management.

## Features
- **Real-time Object Detection**: Utilizes YOLO for quick and accurate identification of products on the conveyor belt.
- **Freshness Analysis**: Employs CNNs to assess product freshness based on visual characteristics such as color and texture.
- **Text Extraction**: Implements OCR to read important product information from labels, including brand, MRP, and expiration dates.
- **Database Integration**: Communicates with a central database via Flask API for product verification and inventory updates.
- **User Dashboard**: Provides a real-time interface using Next.js for monitoring product conditions, inventory levels, and generating alerts for defective products.
- **Continuous Improvement**: Incorporates a feedback loop for model retraining, enhancing accuracy over time based on inspection data.
## System_architecture
![image](https://github.com/user-attachments/assets/470339de-8892-45e2-bca4-0806f4b5479d)
![Untitled Diagram drawio (9)](https://github.com/user-attachments/assets/39fac79e-09a1-4418-96ff-f5cc285f9e92)

## Technology Stack
- **Frontend**: Next.js for the user dashboard.
- **Backend**: Flask API for communication between components.
- **Machine Learning**: 
  - YOLO for object detection.
  - CNNs for freshness classification.
  - SVMs for refining product classification.
  - OCR for text extraction from product labels.
- **Hardware**: 
  - Raspberry Pi 5 for image processing and display.
  - Arduino Mega for motor control and integration with sensors.
  - High-resolution cameras for capturing product images.
  - Ultrasonic sensors for detecting product proximity on the conveyor.

## Hardware Specifications
- **Raspberry Pi 5**: Central processing unit for image preprocessing and display.
- **Arduino Mega**: Controls motors and integrates with ultrasonic sensors.
- **High-Resolution Cameras**: Positioned for comprehensive product imaging.
- **Ultrasonic Sensors**: Measure distance to products for alignment.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/smart-vision-system.git
   cd smart-vision-system
