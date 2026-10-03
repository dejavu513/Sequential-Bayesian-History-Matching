
Method:
This repository contains the code for a simple example of Sequential Bayesian History Matching (SBHM) developed during my PhD.
The main idea of SBHM is to update model parameters when new observations become available, without repeating the whole calibration process from the scratch. 

Example:
The notebook uses a three-degree-of-freedom mass-spring system as a toy example. Two stiffness parameters are treated as unknown and calibrated using observations from the system. 
This is a simple example mainly used to demonstrate how the method works. The method was also tested on a cardio-respiratory model with clinical time-series data in the paper.

Reference:
Cheng, J., DíazDelaO, F. A. and Hristov, P. O. (2025).
Dynamic Model Updating through Reliability-based Sequential History Matching.
Mechanical Systems and Signal Processing, 232, 112689.
