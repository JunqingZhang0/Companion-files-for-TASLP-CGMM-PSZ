# Companion files for TASLP CGMM PSZ

Companion files for the revised paper "CGMM-based Sound Zone Generation using Robust Pressure Matching with ATF perturbation constraints " presented in IEEE/ACM Transactions on Audio, Speech, and Language Processing (under review). The Audio files are generated by the simulations, and the sampling frequency is 16KHz. The audio files have been named according to the type of the source, the application scenario and the algorithm used. eg., Speech_alpha_add_Music_beta(source type) - in_bright_zone(application scenario) - PM_true(algorithm name)

Description:
PM (true) and (ii) PM (measured) correspond to the cases that the PM method is evaluated by the true ATFs and measured ATFs, respectively; (iii) RPM (full) corresponds to the case of the proposed robust pressure matching (RPM) method with an ellipsoidal constraint, and the type of the covariance matrix in such uncertainty constraint is chosen as ‘full’. 

'Speech alpha' is chosen as the desired soundfield within the bright zone, while the 'Music beta' is set as interference. The synthesized audio files of the signal and interference using different methods in the bright zone are provided, e.g., Speech_alpha_add_Music_beta_in_bright_zone_PM_measured.wav; The RPM (full) method can obtain a higher Signal to Interference Ratio (SIR) than the PM (measured), which is consistent with the results shown in the Section V.I. of the manuscript.
