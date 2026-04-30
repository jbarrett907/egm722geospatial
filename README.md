# egm722geospatial
This project requires the installation of both git and conda to the computer. 

Git can be downloaded from Git - Install while conda can be installed as Anaconda Navigator from Download Success | Anaconda if the user prefers a graphical interface, or as a command line interface as miniforge from conda-forge | community-driven packaging for conda. 

The repository for this guide is hosted at: jbarrett907/egm722geospatial
The user should fork and clone the repository using their GitHub account.

Provided in the repository is the environment.yml file that can be used to set up the conda environment. This can be installed directly through Anaconda Navigator by selecting Import in the Environment panel or through running the following command using a command prompt from the cloned directory:
conda env create -f environment.yml
Environment.yml has the following content:
COPY ENVIRON


Once the environment is set up, Jupyter Notebook can be launched which will allow the user to access and run the script. 

This project is licensed under the terms of the MIT license.

The script is set up to use a data zone shapefile and csv file outlining census data. The data files used to test the script are provided in the repository in the data_files folder. The data zone shapefile outlines the geometry of data zones in Northern Ireland for the 2021 census while the census csv file stores data collected in the 2021 census in Northern Ireland.

To run this script, the Northern Ireland shapefiles and census from 2021, 2011, or 2001 can be used, or alternatively similar files can be sourced from the Office of National Statistics for UK census data.
