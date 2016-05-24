# The end of Midcontinent Rift magmatism and the paleogeography of Laurentia
This repository includes data and analysis associated with a manuscript in review entitled **The end of Midcontinent Rift magmatism and the paleogeography of Laurentia** by Luke M. Fairchild, Nicholas L. Swanson-Hysell, Jahandar Ramenzani, Courtney J. Sprain, and Samuel A. Bowring.

This GitHub repository is organized by the following folders.

## Code
This folder includes the data analysis of this project, which utilizes Python 2.7 code within interactive Jupyter notebooks. The bulk of this analysis is presented within the Jupyter notebook ```Late_Rift_Data_Analysis.ipynb```. A separate notebook including bedding and tilt-correction analysis for sampled lava flows of Michipicoten Island can be found within ```Michipicoten_tilt_analysis/Michipicoten_structural_analysis.ipynb```.

Also included is the module pmagpy (version 3.4) which is part of the PmagPy software project (https://github.com/PmagPy). The version of PmagPy used for the analysis is included in this repository and imported for use in the notebook for archival purposes.

To run the code in the notebook it is necessary to both download the code from the Github repository and have an installed Python distribution that includes IPython/Jupyter and the other standard scientific python libraries (http://www.scipy.org/). There are good instructions for installing IPython/Jupyter here: http://ipython.org/install.html. Alternatively you can view the notebooks online with the Jupyter nbviewer:

Paleomagnetic data analysis notebook:
https://nbviewer.jupyter.org/github/swanson-hysell-group/2016_Late_Rift/blob/master/Code/Late_Rift_Data_Analysis.ipynb

Michipicoten bedding/tilt correction analysis:
https://nbviewer.jupyter.org/github/swanson-hysell-group/2016_Late_Rift/blob/master/Code/Michipicoten_tilt_analysis/Michipicoten_structural_analysis.ipynb

## Data
This folder contains paleomagnetic data of this study (MagIC-formatted files), CSV files of previously developed data used in our analysis (see references in manuscript), and reconstruction documents for use within the GPlates software (http://www.gplates.org).

## Additional Notes
- [**PmagPy Open-Source Software License**](./Code/pmagpy_3_4/license.txt)
- The code within the ```Michipicoten_structural_analysis``` Jupyter notebook makes extensive use of the open-source software ```mplstereonet``` developed by Joe Kington (https://github.com/joferkington) and can be viewed/downloaded on GitHub (https://github.com/joferkington/mplstereonet). [**Open-Source Software License for Mplstereonet**](./Code/Michipicoten_tilt_analysis/mplstereonet/LICENSE.txt)
