# AtomS2_Training-Data
# Training data for "Imaging of atomic stress at grain boundaries based on machine learning" 

https://doi.org/10.1016/j.jmps.2023.105455  
Journal of the Mechanics and Physics of Solids, Volume 181, 105455  
Updated by Qingkun Zhao and Zhenghao Zhang, July 1st 2024  
MATLAB

## FILE1: GB_5048_Train.mat

Description: Training data for the stress prediction of 50.48° symmetrical tilt grain boundary (GB) in Au.  
	Data_Origin: Original data from the LAMMPS output.  
	STDD: Mean value and standard deviation of the data.  
	Dist_Norm: The input of BPNN after a Z-Score normalization. Generated from the descriptor matrix describing the local atomic environment information.  
	Label_HydroStress: The label of atomic hydrostatic stress.  
	Label_PotEnergy: The label of potential energy.  

## FILE2: TB_Train.mat

Description: Training data for the stress prediction of twin boundaries in Au.  
	Data_Origin: Original data from the LAMMPS output.  
	STDD: Mean value and standard deviation of the data.  
	Dist_Norm: The input of BPNN after a Z-Score normalization.   
	Label_Mises: The label of von Mises stress.  
	Label_PotEnergy: The label of potential energy.  


## FILE3: GB_20Curv_Train.mat

Description: Training data for the stress prediction of 20° general tilt GBs in Au.  
	STDD: Mean value and standard deviation of the data.  
	Dist_Norm: The input of BPNN after a Z-Score normalization.   
	Label_Mises: The label of von Mises stress.  
	Label_HydroStress: The label of atomic hydrostatic stress.  

