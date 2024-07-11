# Magnetometer-data-estimation

Magnetometer data estimation involves analyzing magnetic field measurements collected by magnetometers. 
These devices are vital across numerous fields, including geophysics, navigation, and aerospace engineering.
By capturing data on magnetic field strength and sometimes direction, magnetometers provide insights into Earth's magnetic field behavior.

Models and parameters:
Gaussian
Gamma
Inverse Gamma
Exponential
Rayleigh

Methods to be implemented for Estimation:
Maximum likelihood
Method of moments

Method of Simulation:
1.Firstly to our dataset, we apply different distribution models.
2.We find the best fit with KL divergence score.
3.GAUSSIAN model has given least KL divergence score for majority of the datasets.
4.For  a single dataset, we find out the best estimator between MLE and MOM using BOX – PLOT.
5.MLE was found to be a better estimator than MOM for both the parameters (mean and variance).
5.For all the remaining datasets, we estimate the parameters by using MLE.




 
