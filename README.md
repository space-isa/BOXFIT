# Plotting notebooks: GRB afterglow lightcurves using BOXFIT 
Jupyter notebooks containing code to plot gamma ray burst (GRB) afterglow lightcurves generated using BOXFIT, a freely-available numerical code. 

# Motivation 
When a pair of binary neutron stars (BNS) collide and merge, they throw off ejecta and trigger the launch of one of the most energetic explosions in the universe: gamma ray bursts. The relativistic jet that's launched first interacts with surrounding ejected matter, before escaping and interacting with the cooler surrounding interstellar medium (ISM). This interaction creates an afterglow which, with a lucky aim and a couple hundred millions of years, eventually reaches our space-based telescopes. The data we recieve on the other hand, however, tell us two things: the amount of energy detected in a given wavelength, and the time at which that energy was detected. Plotting this information gives us the lightcuve signature of that cosmic event. 

Numerical simulations of these observables can help us to back out information about the BNS collision as well as about the structure of the jet that produced the afterglow we detected. There is debate in the astrophysical community as to whether the jet has a "top-hat" shape, or a more structured "winged" shape. Data points to the latter, but we need to model afterglow lightcurves in order to build a solid case. BOXFIT is a numerical code that can generate lightcurves calculated given a range of paramters (observation angle, frequency observed, etc.) and compared to astrophysical data.   

BOXFIT outputs are .txt files with more information than we need, therefore the script must first extract and clean lightcurve (flux) and time data before they can be plotted. This process can be automated while running BOXFIT in batches.   

# About the notebooks  
**Notebook 1** (20190206_lightcurve_test_plots.ipynb): Takes the result of a BOXFIT run and reproduces the plot in Fig.2.1 in the BOXFITv2 User Guide (Eerten, 2016). \
**Notebook 2** (20190320_structured_jet_model.ipynb): Takes the results of three BOXFIT runs to generate a single lightcurve that models a structured jet. 

# How to use

**Notebook 1 (basic plotting)**
1. Download, set up, and run BOXFIT according to the instructions found in the BOXFITv2 User Guide (link in **Credits** section).
2. Use .txt file(s) output as the input to the plotting notebook. Adjust plotting parameters as needed. 
3. Run notebook to view lightcurve plots.  

# Credits 

Link to BOXFIT repo: https://github.com/hveerten/boxfit \ 
Link to BOXFITv2 User Guide: https://cosmo.nyu.edu/afterglowlibrary/boxfitdatav2/boxfitguidev2.pdf

"Gamma-ray burst afterglow broadband fitting based directly on hydrodynamics simulations"
Van Eerten, H.J.; Van Der Horst, A.J.; MacFadyen, Andrew
The Astrophysical Journal, Volume 749, p. 44 (2012)

# Author
Isabel J. Rodriguez, Oregon State University
