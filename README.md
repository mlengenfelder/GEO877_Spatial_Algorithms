# GEO877 Spatial Algorithms Project

This project investigates user behaviors and spatial footprints captured via Flickr metadata across Germany. It specifically contrasts tourist/local geographic density concentrations inside major urban zones against natural administrative recreation areas (parks).

<blockquote style="border-left: 4px solid #1b3fdeff; padding: 8px 16px">
<strong>? Research Question</strong><br>
<em>How does the spatial distribution of photo data differ between cities and parks in Germany in terms of clustering (clustered vs. evenly spread), using the Nearest Neighbor Index (NNI)?</em>
</blockquote>

The main focus of this project is the manual implementation of 3 spatial algorithms, without using geospatial libraries.
Specificly, they are:
* Spatial Indexing
* Point in Polygon
* NNI-Index, using Haversine distance

## Setup Instructions

> [!IMPORTANT]
> Carefully read the setup instructions before proceeding and running the notebook!

<details>

<summary>Show Setup Instructions</summary>

### Step 1: Clone the GitHub Repository to your Desktop

   ```bash
   cd ~/Desktop
   git clone https://github.com/mlengenfelder/GEO877_Spatial_Algorithms
   cd GEO877_Flickr_Project
   ```

<blockquote style="border-left: 4px solid #1f883d; padding: 8px 16px">
💡 <strong>Tip</strong><br>
You can either use this command, or change the directory you want the repository to be placed in (change this: <code>cd ~/Desktop</code>).<br>
Also make sure to run the commands separately!
</blockquote>

### Step 2: Create and activate the environment 

   ```bash
   conda env create -f environment.yml
   conda activate geo877_env
   ```
### Step 3: Initialize the Directory Structure

* Select your newly created environment as Kernel in the notebook. Then only run the very first Cell. This creates the missing folders for the data.

### Step 4: Download and Position the Raw Data

* Now, download the raw data and place it into the raw data folder, you just created by running the firs Cell of the notebook. [Download here](https://drive.google.com/drive/folders/1gX1FCVZ846vzG8BvoCv7m0Nd_13y6k50?usp=share_link) 
* Make sure the DE-Folder is unzipped!
* Place it into: `GEO877_Flickr_Project/data/raw/`
</details>