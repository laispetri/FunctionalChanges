# Data from: Trait-related functional changes in understory forest community after invasion are driven by complementarity rather than displacement

The files in Figshare (https://doi.org/10.6084/m9.figshare.24415648.v3) allow readers to run models to reproduce results and figures of the paper "Trait-related functional changes in understory forest community after invasion are driven by complementarity rather than displacement", currently accepted by Frontiers in Ecology and Evolution (doi: 10.3389/fevo.2024.1325275).

The code to reproduce results and figures can be found at (https://github.com/laispetri/FunctionalChanges.git)

## Description of the data and file structure

The code was built in RMarkdown. All packages needed are listed at the beginning of the code, along with extra information on how to organize folders within the working directory.

Here is the description of the CSV file needed:

* "datafinalLESNoCanopy.csv":
  - type = general description of a forest patch canopy integrity (character);
  - area = forest patch (character);
  - areaID = continuous number ID for each forest patch (integer);
  - transect = original transect number (integer);
  - transectID = continuous transect number (integer);
  - cwmT_leafN_mg.g = community weighted mean of leaf nitrogen content (mg/g) for the total, natives plus invasives, community (double);
  - cwmT_SLA_mm2.mg = community weighted mean of specific leaf area (mm2/mg) for the total, natives plus invasives, community (double);
  - cwmT_LDMC_g.g = community weighted mean of leaf dry matter content (g/g) for the total, natives plus invasives, community (double);
  - cwmN_leafN_mg.g = community weighted mean of leaf nitrogen content (mg/g) for the native community (double);
  - cwmN_SLA_mm2.mg = community weighted mean of specific leaf area (mm2/mg) for the native community (double);
  - cwmN_LDMC_g.g = community weighted mean of leaf dry matter content (g/g) for the native community (double);
  - comm = unique number combining transect and plot numbers (character);
  - commID = unique character combining transect and plot numbers (character);
  - tgfMeanPlot = mean available % light per plot in peak greenness of 2020 (double);
  - tgfSDPlot = standard deviation associated with the mean value of available % light per plot in peak greenness of 2020 (double);
  - smMeanPlotRAW_8 = mean volumetric water content (%) per plot in August of 2020 - driest month (double);
  - smSDPlotRAW_8 = standard deviation associated with mean volumetric water content (%) per plot in August of 2020 - driest month (double);
  - soil_totalN = total soil N (ppm) from resin capsules, values are at the transect level (double);
  - soil_NH4N = soil ammonium (ppm) from resin capsules, values are at the transect level (double);
  - soil_nitrate = soil nitrate (ppm) from resin capsules, values are at the transect level (double);
  - pielou_T = Pielou's Evenness index calculated by plot for the total, natives plus invasives, community (double);
  - pielou_N = Pielou's Evenness index calculated by plot for the native community (double);
  - richness_N = number of native species per plot (double);
  - pctCov_I = percent cover of invasive plant species per plot (double);
  - totalCov = total plant percent cover per plot (double);
  - ID = unique identifier per observation (integer).

Cells with missing data are filled with NAs.

## Sharing/Access information

All four CSV files needed to run this code can be found in Figshare [https://doi.org/10.6084/m9.figshare.24415648.v3].

Please, cite the original paper (once it is published) if using any data or code shared here.
