# EcoAction
DataKindDC project with EcoAction Arlington, through their
[Tree Canopy Fund](https://www.ecoactionarlington.org/community-programs/trees/). The goal is to determine which
neighborhoods to focus on when advertising that EcoAction can provide and plant
trees for free. The intent is to find areas that have low tree-canopy and are
lower-income.

The majority of the documentation and all of the data is stored in Google Drive.
Please reach out to [DataKindDC](https://www.datakind.org/chapters/datakind-dc)
to join the project! 


## Getting Started
After getting access to the google drive folder, clone this repo to your local environment. Then do the following:

1. Unzip the zip files in `EcoAction/data/shape_files/`
1. Download ***EcoAction Arlington/Data/Trees_Planted/tree_data_consolidated - trees.csv*** 
   from Google Drive and place it in `EcoAction/data/` on your local.
1. Set `EcoAction` as the working directory in whatever IDE you are using.

## Repo Structure
### archive/
Contains all old scripts and code that are no longer in active development.

### data/
Relevant demographic, canopy, and shape files for the project

### data/shape_files/
After unzipping these files, you will see a collection of folders that contain shape files. All of these were downloaded from [Arlington County Open Data](https://gisdata-arlgis.opendata.arcgis.com/search).

### scripts/
Scripts that are intended to be run a single time to generate data files or maps.

### src/
The main files of the application, although currently there are only files that contain helper functions.

## Contributing
Take a look at the issues tab in this repo and select one or more to work on. 
When writing code, please do your best to write quality code by following
the [tidyverse style guide](https://style.tidyverse.org/).

We highly recommend that you use pull-requests when commiting new code. 
Pull-requests require that another team member looks at your code, and are almost always
learning experiences for both parties. If you are new to github, pull-requests can 
be somewhat daunting, but it is a learning experience that we hope you won't regret!
Here is more information from github:

* [About pull requests](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
* [Creating a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)





