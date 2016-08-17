# ClimatologyGriddedData.md

Currently we have monthly climatologies available (long-term monthly means, across all years).

## Full-resolution, styled png's intended for tiling (or use as is)

Base url: http://data.nanoos.org/files/cz/mapoverlays/

### 1. PRISM precipitation and mean air temperature

- Monthly files follow a naming pattern like `<variable>_<mm>.png`, where: `variable` = ppt (precipitation) or tmean (air temperature), and `mm` = month (01, 02, ... , 12). 
  - Examples: `ppt_01.png`, `tmean_12.png`
  - Sample url: http://data.nanoos.org/files/cz/mapoverlays/ppt_01.png
- Geographical domain: Continental US (lower 48)
- Geographical extent and cell resolution: TO BE ADDED.
- Much of the remaining information (to be fleshed out here) is found in these json configuration files: http://data.nanoos.org/files/cz/mapoverlays/ppt_climatology.json, http://data.nanoos.org/files/cz/mapoverlays/tmean_climatology.json

### 2. MODIS Enhanced Vegetation Index (EVI)

- Monthly files follow the naming pattern `EVI_<m>.png`, where `m` = month (1, 2, ... , 12).
  - Examples: `EVI_1.png`, `EVI_12.png`
  - Sample url: http://data.nanoos.org/files/cz/mapoverlays/EVI_1.png
- Geographical domain: "Lower North America" (bottom Canada through Central America and theCaribbean islands)
- Geographical extent and cell resolution: TO BE ADDED.
- Much of the remaining information (to be fleshed out here) is found in this json configuration file: http://data.nanoos.org/files/cz/mapoverlays/evi_climatology.json
