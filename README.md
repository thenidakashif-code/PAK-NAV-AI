# PAK NAV AI – Smart Offline Navigation System

## Project Overview
PAK NAV AI is a Pakistan-focused AI-based offline navigation project designed to analyze road conditions and support safer route planning.

## Technologies
- Python
- OpenCV (Computer Vision)
- Scikit-learn (Machine Learning)
- NumPy and Pandas

## Dataset
- RDD2022 India Pothole Dataset: 1,530 annotated images
- BDD100K: Initial road image preprocessing experiments

## Milestone 2 Progress
- Road image preprocessing
- Pothole annotation visualization using XML bounding boxes
- Initial Random Forest model for pothole count estimation
- Model training and testing

## Initial Results
- Images processed for ML: 1,530
- Mean Absolute Error (MAE): 1.3563 potholes
- Example: Actual potholes = 1, Predicted = 1.99

## Current Limitations
The bounding boxes are drawn from existing XML annotations, not automatically predicted by the ML model. The initial ML model estimates pothole counts using simple image features. Offline route navigation and automatic pothole detection remain future development goals.

## Team Members
- Wusqa Adnan
- Nida Kashif
- Talia Batool
- Ayesha Ahmad

## Future Development
- Improved road hazard detection
- Deep learning integration
- Offline Pakistan map and route planning
- Desktop and mobile application

## Project Status
Milestone 2 – Initial Model Development
