# Beyond the Burn: Fire Scars and Social Impacts of the Palisades and Eaton Fires

## Description 
In January 2025, Los Angeles County experienced two catastrophic fires: the Eaton and Palisades Fires. Each fire burned nearly 10,000 acres and forced thousands of residents to evacuate (Neuman, 2025). Strong Santa Ana winds intensified the fires, complicating containment efforts, as the flames not only funneled through mountain passes but also spread over ridges and into surrounding basins (Neuman, 2025). The fires caused widespread displacement, killed at least 28 people, destroyed over 16,000 structures, and inflicted significant ecological damage (Phillips, 2025). 

The purpose of this repository is to store the data, code, and figures used in this assignment, which explores geospatial analysis and manipulation of environmental datasets using Python libraries such as `geopandas` and `xarray`. The project demonstrates how remote sensing data can be processed to create/contrast true color and false color imagery of the Eaton and Palisades Fires, highlighting burn scars and illustrating the role of coding and data visualization in environmental monitoring. By creating false color images from selecting different spectral band types, burned areas are more clearly distinguished from healthy vegetation, providing precise spatial context and a deeper understanding of affected landscapes (Earth Observatory, 2025). 

The repository includes the notebook `hwk4-task2-false-color-SHIRTEKAR.ipynb`, which analyzes geospatial data from both shapefiles and netCDF files to generate true color and false color visualizations of areas affected by the fires in Los Angeles County. The **final output** of the analysis is a map generated using false color imagery of the Eaton and Palisades Fires perimeters. 



## Contents 
This repository is organizated as follows and contains: 
- `README.md`: Markdown file detailing repository description, content, structure, data access, and references.
- `.gitignore`: File alerting Git to avoid "unnecessary" files from being committed to the repository. The data folder containing `landsat8-2025-02-23-palisades-eaton.nc` (Landsat) and fire perimeter spatial data were added to the `.gitignore` to prevent large datasets from being pushed to GitHub. 
- `palisades-eaton-blog-post-SHIRTEKAR.ipynb`: Notebook containing compiled analysis of false color imagery and social dimensions
- `hwk4-task2-false-color-SHIRTEKAR.ipynb`: Notebook containing the analysis of true and false color imagery, as well as finalized false color image map of fire extent in LA County.
- `social-dimensions-eaton-palisades-fires-SHIRTER.ipynb`: 

The structure of the repository is included below.

```
Beyond the Burn: Fire Scars and Social Impacts of the Palisades and Eaton Fires
├── README.md
├── palisades-eaton-blog-post-SHIRTEKAR.ipynb
├── hwk4-task2-false-color-SHIRTEKAR.ipynb
├── social-dimensions-eaton-palisades-fires-SHIRTEKAR.ipynb
├── .gitignore
```

## Data Access
The data utilized in this analysis is not housed in this repository. The streamlined set of spectral bands (red, green, blue, near-infrared, and shortwave infrared) was originally derived from the Landsat Collection 2 Level-2 surface reflectance data, which was atmospherically corrected and captured by the Landsat 8 satellite.The dataset was obtained from the [Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) catalog and cropped to the region encompassing the fire perimeters. It is purely intended for visualization and educational use and is accessible as `landsat8-2025-02-23-palisades-eaton.nc` through the shared resources for the EDS 220 course.

The second dataset consists of geospatial layers containing dissolved fire perimeters for the Eaton and Palisades Fires, provided as shapefiles and downloaded from [County of Los Angeles Enterprise GIS](https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about). It is noted in the data summary that the original NIFC FIRIS fire service contained daily captures of fire perimeters and were thus dissolved from boundary polygons to create a single fire burn perimeter for each fire (County of Los Angeles, 2025).

## Contributors
This repository is maintained by Vedika Shirtekar as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the **EDS 220: Working with Environmental Datasets** course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.


## References
[1] Bren School of Environmental Science and Management. (2025). *landsat8-2025-02-23-palisades-eaton.nc* [Dataset]. Accessed November 20, 2025, from https://drive.google.com/drive/u/1/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP

 
[2] County of Los Angeles Enterprise GIS. (2025). *Palisades and Eaton Dissolved Fire Perimeters (2025)* [Dataset]. County of Los Angeles. Accessed November 20, 2025, from 
https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about


[3] EDS 220. (n.d.). *Working with Environmental Datasets*. Bren School of Environmental Science and Management. Accessed November 29, 2025, from 
https://meds-eds-220.github.io/MEDS-eds-220-course/


[4] Microsoft Planetary Computer. (n.d.). *Landsat Collection 2 Level-2*. Accessed November 20, 2025, from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2


[5] NASA Earth Observatory. (2025, January 16) *The Palisades Fire’s Footprint.*. NASA Earth Observatory. Accessed November 21, 2025, from, 
https://earthobservatory.nasa.gov/images/153831/the-palisades-fires-footprint?


[6] Neuman, S. (2025, January 8). *What are the Santa Ana winds, and how are they impacting the LA wildfires?*. NPR. Accessed November 21, 2025, from 
https://www.npr.org/2025/01/08/nx-s1-5252535/palisades-fire-california-los-angeles-santa-ana-winds


[7] Phillips, S. (2025, February). *The Palisades and Eaton Fires: Neighborhood Data and Potential Housing Market Effects.*. UCLA Lewis Center for Regional Policy Studies. Accessed November 21, 2025, from 
https://escholarship.org/uc/item/1kg4v5v1

