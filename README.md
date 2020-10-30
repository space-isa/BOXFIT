# Plotting BOXFIT gamma ray burst (GRB) afterglow lightcurves 
Jupyter notebooks containing code to plot GRB afterglow lightcurves generated using BOXFIT, a freely-available numerical code. 

# Motivation 
[Talk about structured jet vs tophat] 

The BOXFIT outputs are .txt files with a lot of extraneous information, therefore the script must first extract and clean lightcurve (flux) and time data before they can be plotted. This process can be automated for multiple BOXFIT runs.   

# About the notebook?  
**Notebook 1** (20190206_lightcurve_test_plots.ipynb): Takes the result of a BOXFIT run and reproduces the plot found in Fig.2.1 in the BOXFITv2 User Guide (Eerten, 2016). 
**Notebook 2** (20190320_structured_jet_model.ipynb): Takes the results of three BOXFIT runs to create a lightcurve from a structured jet. 

# How to use

1. Download, set up, and run BOXFIT according to the instructions found in the BOXFITv2 User Guide (link in **Credits** section).
2. Use .txt file(s) output as the input to the plotting notebook. Adjust plotting parameters as needed. 
3. Run notebook to view lightcurve plots.  

# Credits 

Link to BOXFIT repo: https://github.com/hveerten/boxfit
Link to BOXFITv2 User Guide: https://cosmo.nyu.edu/afterglowlibrary/boxfitdatav2/boxfitguidev2.pdf

"Gamma-ray burst afterglow broadband fitting based directly on hydrodynamics simulations"
Van Eerten, H.J.; Van Der Horst, A.J.; MacFadyen, Andrew
The Astrophysical Journal, Volume 749, p. 44 (2012)

# Author
Isabel J. Rodriguez, Oregon State University
