This is the GitHub fot the NCW Epi Consortium's Indicator Dashboard Project.

In this repository, you will find a 'documentation' folder that contains detailed data download and cleaning instructions for each data source and indicator selected by the NCW Epi Consortium. This repository also contains the actual NCW Epi Consortium data cleaning files, as well as the actual data pulled from a variety of secondary sources that are used in these dashboards.

# Requirements to start

## Data folders

It should be noted that data are not stored in the github repository to avoid data security issues.  However, data will be stored within the git repository (folder) on your computer. A single folder named "ncw_data" should be placed in the same folder as this README file.  Additionally inside of the "ncw_data" folder, there should be two folders, one named "raw_data" and one named "cleaned_data".  **If any of these three folders are not present in the dataset or have any other name (i.e. Raw_data or "raw data" are not the same as raw_data) the cleaning scripts will not run**.

## Adding data 

Once the folders have been added as described above, you must place the data sent to you in the "raw_data" folder. If you have not been sent this data, talk to the collaborator you are working with to have them send you the data.

## Cleaning data

Once you have created the data folders and placed the required data in the folders, it is now possible to clean the data. The scripts used to clean the data are stored within the "cleaning_scripts" folder. If you encounter issues when attempting to clean the data, either contact your collaborator or open an issue on the github page.

## Creating PowerBI dashboards

After the clean datasets have been created, data can be read into and displayed by powerBI.
