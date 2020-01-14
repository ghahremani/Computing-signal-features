# Oscillatory_shape_PD_collaborative_project

This project calculates the shape of oscillations and phase-amplitude coupling in deep brain recordings of Parkinson's disease patients. 

Notebooks: 

sharpness_notebook_R.ipynb: notebook to calculate the sharpness for the right STN

sharpness_notebook_L.ipynb: same notebook for the left STN

steepness_notebook_R.ipynb: notebook to calculate the steepness for the right STN

steepness_notebook_L.ipynb: same notebook for the left STN



Libraries: 

filt.py for filtering in the frequency range of interest

shap_L.py and shape_R.py- functions for loading left and right STN data, respectively (i.e. dataL_exc.mat and data_R_exc.mat), running analysis across all subjects, and other miscellaneous tools

shape.py - functions for quantifying the waveform shape of the oscillations. 

plt.py - functions for plotting results

Other files: 
dataL_exc.mat and data_R_exc.mat: data files for the left and right STN, respectively at the clinical contact

ind_LSTN_spec_clinic.png and ind_RSTN_spec_clinic: individual subject power-spectrum at the clinical contact

group_RSTN_spec_clinic and group_LSTN_spec_clinic: group averaged power-spectrum at the clinical contact
