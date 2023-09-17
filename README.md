# Water-confined-density-prediction-APP
This app is a MATLAB app where researchers can predict the confined density of water in carbon nanotubes (CNT).

Researchers can install this app with MATLAB software.

Input parameters and units: temperature (K), pressure (MPa), bulk density of water (Kg/m^3), diameter of CNT (Å), and sigmaC-O (it is optional, and the default value is 3.2865Å).

It should be noted that the CNT is a single-wall CNT, and the diameter of the CNT in the input parameter is the original diameter, not the effective diameter(original diameter minus sigma_CO).

The calculation equations of original diameter D and effective diameter Deff are as follows, where the default C-C bond length acc is 1.42Å.

Output parameters and units: confined density of water (Kg/m^3) and efficient confined density of water (Kg/m^3). For confined density of water, We do not consider the effect of excluded volume, and directly use the original diameter D to calculate the volume of CNT. For efficient confined density of water, We consider the effect of excluded volume, and use the efficient diameter Deff to calculate the volume of CNT.Researchers can choose the density value according to their own situation.

The best prediction range of input parameters: temperature (600-1173 K, and 300 K), pressure (20-30 MPa, and 1 atm), diameter (9.49-50.17 Å).

The origin MD data can be found in excel file (DATA_SET.xlsx). User can use "APP_ML_predict_CNT_confined_density.mlappinstall" file to install this APP in MATLB, or use "APP_ML_predict_CNT_confined_density.mlapp" and "net.mat" to directly use this APP in MATLAB.

If you have any questions, please contact zbwxjtu@163.com.
