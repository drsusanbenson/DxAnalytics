DATA ANALYTICS FOR CLINICAL HISTORY DATA

Files:
1) DictAlgorithm.rmd - R markdown file containing the algorithm
2) BloodCultureClinHxDataset.csv - Blood Culture dataset
3) ClinHxDictionary.csv - Dictionary file
4) ModelOutput.csv - Output of DictAlgorithm

written in R version 4.0.2 (2020-06-22).
readr, quanteda, tm, and stringr are required for usage.

Packages can be installed using the chunk labelled package-installation. This needs to be done once.


To run the code the files, need to be correctly named:
1)  Blood culture dataset (BloodCultureClinHxDataset.csv)
2)  ClinHx Dictionary (ClinHxDictionary.csv)


The dictionary can be modified accordingly to add words as necessary, using the format provided.
 
The dataset can be swapped out if column names remain the same 



To use the algorithm:

1) Upload blood culture data to the directory and rename it (Only if new data is being used).

2) Open R studio and load DictAlgorithm.rmd file

3) If being run for the first time run the package installation chunk on line 8 to 17. This is done with the green arrow on the right of the box.

4) Once packages are installed run the Algorithm chunk on line 20 by pressing the green arrow. The code will take some time to run.

5) The output will be saved as ModelOutput.csv. If another file with the same name exists it will be replaced.


 

