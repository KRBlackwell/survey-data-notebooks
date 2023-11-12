# survey-data-notebooks
This repository is for self-contained notebooks that use survey data from various sources, for example the National Survey of Children's Health (NSCH).

## nsch_physical_activity.ipynb
How to get weighted and unweighted estimates in Python\
Using 2022 data from the National Survey of Children's Health\
PHYSACTIV = Physical Activity Ages 6-11\
This notebook shows how to import SAS data and metadata to a dataframe using pyreadstat, save it to disk, read files back in from disk, 
### Assumptions:
* You have packages installed
* You haven't read the data in already
* C:\nsch exists
* Windows zip
### Configure
* Comment out the lines for "Set Up - pip install and import" if you need to install packages
* Once you read the data in, "Read in data" "The first time, we'll save to disk." You will comment those lines out and uncomment the lines under "Read in data" "after saving to disk"
* Create C:\nsch or create a different place to save the data and change the code at #set some paths, files, and a variable, my_dir = "C:/nsch"
