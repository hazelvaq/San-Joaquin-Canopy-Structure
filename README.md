# Lidar Validation

<img src="https://github.com/hazelvaq/San-Joaquin-Canopy-Structure/assets/108312152/87ad5ced-3346-478d-afd0-c27a8565afcb" width="800" height="400">

[*Lidar Canopy Image*](https://resilience-blog.com/2022/07/06/how-we-can-better-understand-our-forest-ecosystems-with-laser-scanning/)


This project analyzes the accuracy of Landsat tree canopy height by comparing it to on-the-ground field surveys. The scope of area is the San Joaquin Experimental Range in 
California. This project was completed in R. The steps of this project include:

- raster manipulation
- spatial joining
-  Using `tmap` for visualization
-  Linear regression modeling plot


# Citations
Data was obtained from The National Science Foundation's [National Ecological Observatory Network (NEON)](https://www.neonscience.org/about).
This project is based on [materials](https://www.neonscience.org/resources/learning-hub/tutorials/introduction-light-detection-and-ranging-lidar-explore-point) developed by Edmund Hart, Leah Wasser, and Donal O'Leary for NEON.

# File Structure
```markdown
├── data
│   ├── PlotCentroids
│   │   ├── SJERPlotCentroids_Buffer.dbf
│   │   ├── SJERPlotCentroids_Buffer.prj
│   │   ├── SJERPlotCentroids_Buffer.sbn
│   │   ├── SJERPlotCentroids_Buffer.sbx
│   │   ├── SJERPlotCentroids_Buffer.shp
│   │   ├── SJERPlotCentroids_Buffer.shp.xml
│   │   └── SJERPlotCentroids_Buffer.shx
│   ├── SJER2013_DSM.tif
│   ├── SJER2013_DTM.tif
│   └── VegetationData
│       ├── D17_2013_vegStr.csv
│       └── D17_2013_vegStr_metadata_desc.csv
├── README.md
├── San-Joaquin-Canopy-Structure.Rproj
├── tree_canopy.html
└── tree_canopy.Rmd
```
