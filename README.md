# Visualizing the Extent of the Palisades and Eaton Fires in Los Angeles County

## Description 
In January 2025, Los Angeles County experienced two catastrophic fires: the Eaton and Palisades Fires. Each fire burned nearly 10,000 acres and forced thousands of residents to evacuate (Neuman, 2025). Strong Santa Ana winds intensified the fires, complicating containment efforts, as the flames not only funneled through mountain passes but also spread over ridges and into surrounding basins (Neuman, 2025). The fires caused widespread displacement, killed at least 28 people, destroyed over 16,000 structures, and inflicted significant ecological damage (Phillips, 2025). 

The purpose of this repository is to store the data, code, and figures used in this assignment, which explores geospatial analysis and manipulation of environmental datasets using Python libraries such as `geopandas` and `xarray`. The project demonstrates how remote sensing data can be processed to create/contrast true color and  false color imagery of the Eaton and Palisades Fires, highlighting burn scars and illustrating the role of coding and data visualization in environmental monitoring. The repository includes the notebook `hwk4-task2-false-color-SHIRTEKAR.ipynb`, which analyzes geospatial data from both shapefiles and netCDF files to generate true color and false-color visualizations of areas affected by the fires in Los Angeles County. The **final output** of the analysis is a map generated using false color imagery of the Eaton and Palisades Fires perimeters. 

## Contents 
This repository is organizated as follows and contains: 
- `README.md`: Markdown file detailing repository description, content, structure, data access, and references.
- `.gitignore`: File alerting Git to avoid "unnecessary" files from being committed to the repository. The data folder containing `landsat8-2025-02-23-palisades-eaton.nc` (Landsat) and fire perimeter spatial data were added to the `.gitignore` to prevent large datasets from being pushed to GitHub. 
- `hwk4-task2-false-color-SHIRTEKAR.ipynb`: Notebook containing the analysis of true and false color imagery, as well as finalized map of fire extent in LA County.

The structure of the repository is included below.

```
eds220-hwk4
├── README.md
├── hwk4-task2-false-color-SHIRTEKAR.ipynb
├── .gitignore
```

## Data Access

(1 pt) Details regarding data access. Any necessary information on where data lives (e.g. is it housed in the repo, on a server, in a library / package etc.) and how to access it in order to run the code.



## References
(1 pt) References or acknowledgements. In an appropriate, consistent format, including links. Provide a reference to the course and any other sources that supported the development of the repository. Add references for data sets too.

(3 pts) Throughout, the GitHub repository’s README should be free of typos, grammatical errors, and formatting mistakes. Appropriate markdown and markdown headers are  used to enhance the readability All content in the README is contained under a respective header in order to clearly access information. The overall flow of the README guides the viewer through the repository and is easy to follow. 
 
