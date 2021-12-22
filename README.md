# Dashboard Visualisation

This dashboard's goal is to provide charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in Toronto.

The property data was retrieved from the following websites:

* [Toronto Open Data](https://open.toronto.ca/)

* [Census Profile, 2016 Census - Toronto Metropolitan Area, Ontario and Canada](https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CMACA&Code1=535&Geo2=PR&Code2=01&SearchText=toronto&SearchType=Begins&SearchPR=01&B1=All&TABID=1&type=0)


Calculations and visualizations were initially performed in `src/rental_analysis.ipynb`. The `src/dashboard.ipynb` is used to create a dashboard of interactive visualizations to explore the market data.

## Installation

### Requirements
- Anaconda. See the [Anaconda Installation Guide](docs/AnacondaInstallGuide.md) for more details.
- PyViz. See the [PyViz Installation Guide](docs/PyVizInstallationGuide.md) for more details.
- You will also need to register for a public mapbox API key, which can be obtained via [this sign-up link](https://account.mapbox.com/auth/signup/).

## Dashboard Demo
1. Fork or clone the repo
2. Rename `.env.example` to `.env` and store your mapbox api token in the file.
3. Activate the pyviz conda environment. If it is named `pyvizenv`:
   - `conda activate pyvizenv`
4. From the command line change directory into the repo's `src` folder
   - `cd /path/to/dashboard-viz/src`
5. Run the bash script
   - `bash run.sh`
6. The dashboard should open up in the default web browser. If not, try navigating to [http://localhost:5006/dashboard](http://localhost:5006/dashboard) from your browser url bar.
