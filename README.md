egm722geospatial

Overview:
egm722geospatial is a project that assesses census data to produce statistical and visual outputs of the distribution of population density. This is a metric that is influential to environmental planning and therefore awareness of distribution can be essential.


Installation and Setup:
This project requires the installation of both git and conda to the computer.
The repository for this guide is hosted at: jbarrett907/egm722geospatial
The user should fork and clone the repository using their GitHub account and follow the script. 


Environment.yml:
Provided in the repository is the environment.yml file that can be used to set up the conda environment. This can be installed directly through Anaconda Navigator by selecting Import in the Environment panel or through running the following command using a command prompt from the cloned directory:
conda env create -f environment.yml

Environment.yml has the following content:
name: egm722geospatial
channels:
  - conda-forge
  - defaults
dependencies:
  - python
  - geopandas
  - pandas
  - cartopy
  - matplotlib

Once the environment is set up, Jupyter Notebook can be launched which will allow the user to access and run the script. 


Data:
The script is set up to use a data zone shapefile and csv file outlining census data. The script was tested using data relevant to the Northern Ireland 2021 census which is available in the data_files folder. 
 - The data zone shapefile outlines the geometry of data zones in Northern Ireland for the 2021 census
 - The census csv file stores data collected in the 2021 census in Northern Ireland.

Alternative datasets include Northern Ireland shapefiles and census from 2021, 2011, or 2001, or alternatively similar files can be sourced from the Office of National Statistics for UK census data.


License:
This project is licensed under the terms of the MIT license.

