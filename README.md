# Heart_disease_prediction
# Heart Disease Prediction Analysis

## Overview
This repository contains Python code and analysis focused on predicting heart disease using a specific dataset. The analysis was performed using Google Colab, which allows for an interactive environment that can be easily shared and accessed.

## Data
The dataset used in this analysis is titled 'Heart_Disease_Prediction.csv'. It includes various health-related attributes that are indicative of heart disease presence in patients.

## Features
- Data loading and preprocessing
- Trend analysis based on visit dates
- Demographic analysis correlating age and heart disease incidence
- Investigation into chest pain types associated with heart disease
- Blood pressure and cholesterol level analysis in the context of heart health
- Impact assessment of diabetes on heart health
- EKG results patterns and their relation to heart disease
- Examination of exercise impact on heart health

## Analysis Performed
- The data is initially loaded by skipping the first 6 rows, including only the first 250 rows, parsing 'Visit Date' as a date type, and setting 'Patient_ID' as the index.
- A trend analysis is conducted to observe the prevalence of heart disease over time.
- Demographic and chest pain type analyses are performed to see relationships with heart disease.
- Blood pressure and cholesterol levels are analyzed to understand their correlation with heart disease.
- Diabetes impact on heart health is investigated by comparing patients with a fasting blood sugar over 120 to those with normal FBS levels.
- EKG results are examined to identify patterns in patients diagnosed with heart disease.
- The relationship between the maximum heart rate during exercise and heart disease is assessed.

## Visualization
Various plots and visualizations are included to illustrate the findings, such as trend lines, bar charts, and heatmaps.

## Requirements
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage
To replicate the analysis, mount your Google Drive in Colab and adjust the `file_path` variable to point to the location of the 'Heart_Disease_Prediction.csv' file in your drive.

## Note
Warnings from the data processing steps, such as parsing date formats or coercion of data types, have been noted and should be taken into account when re-running the analysis.

## Contributing
Feel free to fork this repository, and contributions to enhance the analysis are welcome.

## License
This project is open source and available under the [MIT License](LICENSE).

