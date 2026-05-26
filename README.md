# GEO877 Spatial Algorithms Project

## Research Question
> **How does the spatial distribution of photo data differ between cities and parks in Germany in terms of clustering (clustered vs. evenly spread), using the Nearest Neighbor Index (NNI)?**

This project investigates user behaviors and spatial footprints captured via Flickr metadata across Germany. It specifically contrasts tourist/local geographic density concentrations inside major urban zones against natural administrative recreation areas (parks).

The main focus of this project is the manual implementation of 3 spatial algorithms, without using geospatial libraries for them.

Specificly, they are:
* Spatial Indexing
* Point in Polygon
* NNI-Index, using Haversine distance

---

## Setup Instructions

This project requires a robust geometric stack managed via a Conda Environment.

1. **Clone the GitHub Repository to your Desktop** 

   ```bash
   cd ~/Desktop
   git clone https://github.com/mlengenfelder/GEO877_Spatial_Algorithms
   cd GEO877_Flickr_Project
   ```

2. **Create and activate the environment** 

   ```bash
   conda env create -f environment.yml
   conda activate geo877_env
   ```
3. **Initialize the Directory Structure**

* Select your newly created environment as Kernel in the notebook. Then only run the very first Cell. This creates the missing folders for the data.

4. **Download and Position the Raw Data**

* Now, download the raw data and place it into the raw data folder, you just created by running the firs Cell of the notebook.
* Make sure the DE-Folder is unzipped!
* GEO877_Flickr_Project/data/raw/