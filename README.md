# FNO Field prediction

#Motivation 

Numerical simulations for photonic structures are computationally
expensive. One of the reasons is that the wavelength of
light is in 500 nm scale. In order to achieve valid simulation results
of light intensity distribution, the mesh size need to be of 1 nm
scale, in order to study the variation of light intensity. On the other
hand, many photonic structures have sizes larger than 10 um scale,
leading to an extremely large mesh number in the simulation. For
example, in 3D simulation, a mesh by 10 um in each side (x,y,z)
with 1 nm mesh size on average, will need to compute the light
intensities among O(10^12) points. This greatly limits the study of
light intensity distribution in photonic structures.
This work uses a Fourier Neural Operator  to predict the field intensity of a dielectric particle inside a micro F-P cavity. 
![alt text](https://github.com/pandaman0w0/FNO_Field_prediction/blob/main/readme_img1.png)


#description of files

This code is modified from FNO available here: https://github.com/AI-Complexity-Lab/cse598/tree/main/hw1
The file test of FNO performs data visualization and model saving. 
The model size/ layers etc. need to match between the two files. 
The last section need to load experimental data and perform data linear interpolation. 
