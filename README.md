# BRIL

This is the analysis code generated to study the output from https://github.com/gauzinge/BRIL_ITsim branch jcordero

*Note that all the code in this repository is in the form of jupyter notebooks*

You can convert them jupyter notebooks to python script using `jupyter nbconvert --to script [NAME].ipynb` but this is not advised, since the format of the current script was not created with the intent to be ran as a standalone pyhton script. 

## Content of this repository 

### BRILanalyzer.ipynb 

:warning: This is a very slow code
:warning: This is a old code that was made before working on the stand alone simulation of the hits and cluster counts, having said that it should be functional

Analysis code to fit a CB distribution to the cluster counts for each disk and ring 

### BRIL_Ana.ipynb 

:warning: The code generates output figures and will not run if the proper output structure is not there or if the code is not modified to acomodate the local structure of your machine.


**Description**
Analysis code used to study the several Cluster variables, input for this analysis can be found in `/eos/user/c/corderom/BRIL/local/` 

Focus on the R-projection of the disks. Care was taken to normalize for the number of modules per ring and  eliminating the gaps between rings




 
