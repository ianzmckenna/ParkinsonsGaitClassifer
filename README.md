# Parkinsons Gait Classifier

A machine learning project for detecting Parkinson's disease based on gait patterns using smartphone accelerometer and gyroscope data.

### Overview
This project implements classification algorithms to detect Parkinson's disease by analyzing movement patterns from mobile sensor data. By processing accelerometer and gyroscope readings collected during walking, the system can identify characteristic gait abnormalities associated with Parkinson's disease.

### Dataset
The dataset consists of accelerometer and gyroscope measurements collected from both healthy individuals and Parkinson's disease patients. The data structure includes:

- **Accelerometer data: Walking patterns captured as triaxial accelerometer readings**
  - 3-axis motion data (X, Y, Z) sampled at regular intervals
  - Separate files for healthy subjects and Parkinson's patients

- **Gyroscope data: Angular velocity measurements during walking**
  - 3-axis rotational data (X, Y, Z) sampled at regular intervals
  - Separate files for healthy subjects and Parkinson's patients
  
Data is organized as follows:
- Individual CSV files for each recording session
- Aggregated data files (all_accel_data.csv and all_gyro_data.csv)

### Methodology
The analysis pipeline is implemented in parkinson_detection.ipynb and includes:
- Data preprocessing and cleaning
- Feature extraction from raw sensor data
- Feature selection to identify the most discriminative patterns
- Classification model training and evaluation
- Performance assessment using metrics like accuracy, sensitivity, and specificity
  
### Installation and Usage
Requirements
```
numpy
pandas
scikit-learn
matplotlib
jupyter
```
Running the Analysis
- Clone this repository
- Install the required dependencies
- Launch Jupyter Notebook: jupyter notebook
- Open parkinson_detection.ipynb
- Run all cells to reproduce the analysis

### Results
The classifier demonstrates the ability to distinguish between healthy subjects and individuals with Parkinson's disease based on gait characteristics. Detailed results, including performance metrics and feature importance, are available in the Jupyter notebook.

### Future Work
- Expand the dataset with more subjects and varied walking conditions
- Implement real-time classification for mobile applications
- Explore deep learning approaches for feature extraction

### Contributors
Ben Souferian and Jonathan Chien
