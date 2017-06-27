# ClimatologyGriddedData.md

Currently we have monthly climatologies available (long-term monthly means, across all years).

Some clarifications:
- Currently we have long-term monthly climatologies (means or totals across years). Anthony and I agreed that was a good place to start. We could probably also create annual means or totals (across all years, per year, or both) fairly easily, say within the next 3 weeks; we'd first have to decide if that's a priority.
- In the meantime, we already have png's we can share right away, intended for tiling. With a bit more effort, but probably quite easily, we could also provide geotiff's with actual data values to be used for analysis. We are also working on cleaning up the Python code to share it via github; that will take us another couple of weeks.

## Full-resolution, styled png's intended for tiling (or use as is)

Base url: http://data.nanoos.org/files/cz/mapoverlays/

### 1. PRISM precipitation and mean air temperature [AN81m]

- Monthly files follow a naming pattern like `<variable>_<mm>.png`, where: `variable` = ppt (precipitation) or tmean (air temperature), and `mm` = month (01, 02, ... , 12). 
  - Examples: `ppt_01.png`, `tmean_12.png`
  - Sample url: http://data.nanoos.org/files/cz/mapoverlays/ppt_01.png
- Geographical domain: Continental US (lower 48)
- Geographical extent and cell resolution: [-125.0208333333334991, 24.0575000000025021, -66.4608333333334969, 49.9375000000025011], Pixel Size: 0.04 or 4km
- Much of the remaining information (to be fleshed out here) is found in these json configuration files: http://data.nanoos.org/files/cz/mapoverlays/ppt_climatology.json, http://data.nanoos.org/files/cz/mapoverlays/tmean_climatology.json

[Official Documentation](http://prism.nacse.org/documents/PRISM_datasets.pdf)

### 2. MODIS Enhanced Vegetation Index (EVI) [MOD13A3]

- Monthly files follow the naming pattern `EVI_<m>.png`, where `m` = month (1, 2, ... , 12).
  - Examples: `EVI_1.png`, `EVI_12.png`
  - Sample url: http://data.nanoos.org/files/cz/mapoverlays/EVI_1.png
- Geographical domain: "Lower North America" (bottom Canada through Central America and theCaribbean islands)
- Geographical extent and cell resolution: [-127.8294048826629989, 5.1830409679864857, -59.0561278820333229, 49.9999999955067977], Pixel Size: 0.01 or 1km
- Much of the remaining information (to be fleshed out here) is found in this json configuration file: http://data.nanoos.org/files/cz/mapoverlays/evi_climatology.json
