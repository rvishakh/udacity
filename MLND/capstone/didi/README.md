# Capstone Project - Machine Learning Nano Degree
#### Vishakh Rayapeta

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

## Notebooks Summary
The following order can be used to browse the notebooks:

#### Data Processing & Exploration
data\_processing.ipynb
data\_exploration.ipynb

#### Basic Algorithm Implementations w/ Initial Parameter Tuning
implement\_basic.ipynb
implement\_nn.ipynb
implement\_nn2.ipynb
implement\_nn3.ipynb

#### Analysis of Basic Algorithm Implementations
residual\_analysis.ipynb

#### Refinements
refine\_addgap.ipynb
refine\_sqrt.ipynb
refine\_addtimeweek.ipynb
refine\_paramtune.ipynb
refine\_featred.ipynb
refine\_nn3.ipynb
refine\_ensemble.ipynb

#### Evaluation of Final Models
model\_eval.ipynb