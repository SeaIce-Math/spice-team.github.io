---
title: Software
layout: default
---
## Software projects

- Graph-theoretic algorithms for Kolmogorov operators, available as part of [MUQ---see branch "andyddavis/graph-theoretic-algorithms"](muq.mit.edu/)

- Kernel methods for feature extraction and forecasting in dynamical systems.
[https://github.com/dg227/NLSA](https://github.com/dg227/NLSA)
 
- Subzero DEM using polygons in Matlab.
[https://github.com/SeaIce-Math/SubZero](https://github.com/SeaIce-Math/SubZero)

- MATLAB Live Script for segmentation of individual sea-ice floes in imagery (See related segmentation products below). [https://doi.org/10.5281/zenodo.6146144](https://doi.org/10.5281/zenodo.6146144) 

## Data Products

### Sea-Ice Floe Segmentation Products

These products are derived from high-resolution optical images acquired over the Arctic Canada Basin and disseminated by the United States Geological Survey Global Fiducials Library [(https://www.usgs.gov/core-science-systems/nli/global-fiducials-library)](https://www.usgs.gov/core-science-systems/nli/global-fiducials-library). They contain individually identified sea-ice floes; various floe properties may easily be retrieved from them, including floe number, area, diameter, and shape (area is provided with the products already). For a full description of the products, see Denton and Timmermans (2021, [preprint](https://doi.org/10.5194/tc-2021-368)). The products are available at [https://doi.org/10.5281/zenodo.6341620](https://doi.org/10.5281/zenodo.6341620).

A preview of the products is provided below.

<center><img src="/images/sea_ice_floe_products/display_miz02a620250aws02_20140424_m_fr_bwthresh05_strel1_25e_halfstep_labeled_rgb.png" alt="" width="50%"></center>

### Library of sea ice floe remote sensing observations in the Beaufort Sea Marginal Ice Zone

These products contain a collection of geometrical and kinematic sea ice floe measurements for the analysis in the paper, "Spinning sea ice floes reveal emerging mesoscale turbulence in the Arctic Ocean" (accpeted to Scientific Reports). These observations were retrieved from processed MODIS imagery using our Ice Floe Tracking algorithm. For a full description of the products, see " "Ice Floe Tracker: An algorithm to automatically retrieve Lagrangian trajectories via feature matching from moderate-resolution visual imagery" [(Lopez-Acosta et al., 2019)](https://www.sciencedirect.com/science/article/abs/pii/S0034425719304250). The products are available at [https://zenodo.org/record/4796845#.Ykxp0ujMIuV](https://zenodo.org/record/4796845#.Ykxp0ujMIuV)

<center><img src="/images/Ice_floe_tracker_products/Ice_floe_tracker.png" alt="" width="80%"></center>

### SOIT: Satellite Overpass Identification Tool

The Satellite Overpass Identification Tool (SOIT) is a Python-based program for identifying the daytime overpass time of the Aqua and Terra satellites closest to a point of interest for a given range of dates. Using [Skyfield](https://rhodesmill.org/skyfield/) (an existing Python orbital mechanics package) and [Space-Track.org](https://www.space-track.org/) (an online source of satellite data), the program determines the precise overpass times for Aqua and Terra. The algorithm can be easily modified to retrieve data for other satellites. The products are available at [https://zenodo.org/record/6475619#.YmFw9NrMKUk](https://zenodo.org/record/6475619#.YmFw9NrMKUk)_

An example of the products is provided below.

<b>[Input configuration]</b>

start date = 04/01/2021

end date = 04/02/2021

latitude of interest = 72

longitude of interest = -18

<b>[Output]</b>

Acquired satellite overpass time = (Aqua) 13:08:03 (Terra) 12:47:55

For comparison, this is the information that can be found in EOSDIS:

<center><img src="/images/SOIT_products/SOIT_EOSDIS.png" alt="" width="80%"></center>
