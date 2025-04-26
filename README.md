# Activity-Recognition-Feature-Analysis-Hypothesis-Based-Feature-Significance-Testing
This project analyzes motion sensor data (e.g., head, wrist, and foot rotations) to identify statistically significant features for human activity classification. Using **ANOVA (Analysis of Variance)**, it tests whether features like `Head_Rx`, `L_Wrist_Ry`, etc., vary significantly across different activities.

## Key Features
- Performs **ANOVA tests** to evaluate feature importance (`p < 0.05`).  
- Visualizes variances of significant features using bar plots.  
- Designed for datasets with **IMU sensor data** (e.g., gyroscope/accelerometer).  

## Use Cases
- Optimizing feature selection for activity recognition models.  
- Validating sensor data quality in healthcare, sports, or AR/VR applications.  
