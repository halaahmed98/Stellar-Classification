# Stellar Classification Sloan Digital Sky Survey DR17
Stellar classification is the classification of stars based on their spectral characteristics. The classification scheme of galaxies, quasars, and stars is one of the most fundamental in astronomy

## Dataset
The dataset is collected from Kaggle:  
https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17?datasetId=1866141&sortBy=voteCount

## Feature Description
1. `obj_ID `= Object Identifier, the unique value that identifies the object in the image catalog used by the CAS
2. `alpha` = Right Ascension angle (at J2000 epoch)
3. `delta` = Declination angle (at J2000 epoch)
4. `u` = Ultraviolet filter in the photometric system
5. `g` = Green filter in the photometric system
6. `r` = Red filter in the photometric system
7. `i` = Near Infrared filter in the photometric system
8. `z` = Infrared filter in the photometric system
9. `run_ID` = Run Number used to identify the specific scan
10. `rereun_ID` = Rerun Number to specify how the image was processed
11. `cam_col` = Camera column to identify the scanline within the run
12. `field_ID` = Field number to identify each field
13. `spec_obj_ID` = Unique ID used for optical spectroscopic objects (this means that 2 different observations with the same spec_obj_ID must share the output class)
14. `class` = object class (galaxy, star or quasar object)
15. `redshift` = redshift value based on the increase in wavelength
16. `plate` = plate ID, identifies each plate in SDSS
17. `MJD` = Modified Julian Date, used to indicate when a given piece of SDSS data was taken
18. `fiber_ID` = fiber ID that identifies the fiber that pointed the light at the focal plane in each observation
Citation


## Install Dependencies

Install the dependencies:

```
pip install -r requirements.txt
```

## Run the Jupyter Notebook

Run Jupiter notebook using the following command assuming we are inside the project directory:

```
jupyter notebook
```
