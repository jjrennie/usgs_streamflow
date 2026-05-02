# Download and Plot Streamflow Data from USGS
## Written By Jared Rennie (@jjrennie)

Taps into the <a href='https://dashboard.waterdata.usgs.gov/app/nwd/en/' target='_blank'> USGS National Water Dashboard</a> to get river gauge streamflow, statistics and metadata. 

- API Documentation: https://waterservices.usgs.gov/
  
## Importing Packages <a class="anchor" id="first-bullet"></a>
First off, the entire codebase works in Python 3. In addition to base Python, you will need the following packages installed: 
- pandas and numpy (to slice and dice the data)
- matplotlib and cartopy (to plot the data)

The "easiest" way is to install these is by installing <a href='https://www.anaconda.com' target="_blank">anaconda</a>, and then applying <a href='https://conda-forge.org/' target="_blank">conda-forge</a>. Afterward, then you can install the above packages. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjrennie/usgs_streamflow/HEAD?urlpath=%2Fdoc%2Ftree%2Fusgs_streamflow.ipynb)
