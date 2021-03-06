MLSoilCO2Flux

Name of the program: Machine Learning Algorithm for Simulating Soil CO2 Fluxes (MLALSoilCO2) 
Author: Toby Adjuik Department of Biosystems and Agricultural Engineering, 
University of Kentucky, Lexington, KY 40503, United States.

This repository contains machine learning based models (MLSoilCO2Flux) that predict CO2 fluxes from cropping systems. 
Detailed description of this work is available in our paper: 
Adjuik, T.A., Davis, S.C. Machine Learning Approach to Simulate Soil CO2 Fluxes under Cropping Systems. 
Agronomy 2022, 12, 197, doi: https://doi.org/10.3390/agronomy12010197

Packages to install before using the code
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit Learn
6. matplotlib.pyplot
7. mlxtend
8. scipy


Running the script

1. Set the working directory to the directory where your Measured_GHG_Fluxes_ML data is stored. 
This involves modifying this line in the code: "pd.read_csv(r"D:\Data\Measured_GHG_Fluxes_ML.csv")"

2. During data cleaning, you will be prompted to save your dataframe to your working directory using this line code
New_GHG_Data.to_csv("New_GHG_Data.csv").

3. Reupload the saved file using this line of code: New_GHG_Data=pd.read_csv(r"D:\Data\New_GHG_Data.csv")
