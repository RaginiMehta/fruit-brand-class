# Juice Brand Project

This repository contains **4 files** that together demonstrate a simple juice brand project.

Each file is responsible for a specific part of the project logic and structure, Analysing and processing data, arrangement, and, analysis and plotting as required.  

Ultimately the aim of the project is the understanding of intrinsic sugar profiles for analysis and succesful classfications for numerous applications.

This project is intended for learning and practice purposes.

## Files

The files are : 

1. ```impNph.ipynb``` : This script is used for division of the data between impedance and phase values, based on timestamps of data collection, on the basis of classes and eventually into real and imaginary data.

2. ```LDA.ipynb```: This script is used for analysis of data, with the creation of LDA Plots on the different data collected, and furthermore on the KNN Classification and analysis.

3. ```NyquistPlot.ipynb```: This plot is utilised for Nyquist Plotting and serves as an important intial step in the direciton of the project.

## Project Workflow / Pipeline

The overall workflow of the project follows a structured data analysis and classification pipeline:

1. **Data Collection**  
   Impedance spectroscopy data is collected from multiple juice samples, including impedance magnitude, phase values, frequency information, and timestamps.

2. **Data Preprocessing**  
   The raw data is divided into impedance and phase components based on timestamps and class labels. The data is further transformed into real and imaginary components to enable advanced analysis.

3. **Nyquist Plot Analysis**  
   Nyquist plots are generated to visualize the impedance behavior of different juice samples. This step provides an initial qualitative understanding of the electrical characteristics and class separability.

4. **Feature Analysis Using LDA**  
   Linear Discriminant Analysis (LDA) is applied to reduce dimensionality and enhance class separability by identifying the most discriminative features in the dataset.

5. **Classification Using KNN**  
   A K-Nearest Neighbors (KNN) classifier is implemented to evaluate the effectiveness of the extracted features in accurately classifying juice samples.

6. **Performance Evaluation**  
   Classification results are analyzed to assess model accuracy and overall feasibility of impedance-based juice classification.


## Conclusion

This project demonstrates the potential of impedance spectroscopy combined with statistical and machine learning techniques for distinguishing between different juice samples. The use of Nyquist plots and Linear Discriminant Analysis provides valuable insight into the underlying electrical properties and feature separability, while KNN classification highlights the practicality of this approach for real-world applications.

Overall, the Juice Brand Project establishes a foundational framework for sensor-based food analysis and opens avenues for future enhancements such as incorporating additional classifiers, expanding the dataset, and optimizing feature extraction techniques.