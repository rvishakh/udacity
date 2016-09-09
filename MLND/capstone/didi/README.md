## Capston Project - Machine Learning Nano Degree
### Vishakh Rayapeta

## Location of input data files
### Original datafiles
https://www.dropbox.com/s/2siw06sa5mo2zvw/citydata.tar.gz?dl=0

The original files are used by data\_processing.ipynb. Update the data\_dir variable in the notebook to point to the current location of the unzipped data folder.

### Pickle file
The original data is processed and saved as data\_set.pickle on the github folder. All subsequent python notebooks use this pickle file to access the data.


## Library dependencies
sklearn    0.17.1    
pandas     0.18.0    
numpy      1.11.1     
tensorflow 0.9.0    
seaborn    0.7.0    

Versions of tensorflow newer than 0.9.0 may be incompatible.

## Machine requirements
* c4.8xlarge instance (36 CPUs, 60GB RAM) was used to speed up results and run multiple experiments.    
* 4GB to 8GM RAM is needed to execute most algorithms with 2 to 4 CPUs. More RAM is needed as CPU count increases.
* Using fewer CPUs will reduce the amount of parallel computing and lead to longer runtimes.
