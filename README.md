# About the dataset.

## Transients Objects

For the Transients objects, you can find in the fits images' headers the next information: 

| Header Dict | Description                                  |
|-------------|----------------------------------------------|
| CRTS_ID     | Catalina Real-time Transient Survey  ID.     |
| RA_(J2000)  | Right Ascension (degrees).                   |
| Dec_(J2000) | Declination (degrees).                       |
| N_Images    | Total number of images for this CRTS ID.     |
| UT_Date     | Discovery Date.                              |
| Mag         | Unfiltered CSS magnitude.                    |
| CSS_Images  | Pre and post-discovery images.               |
| SDSS        | Covered by SDSS DR-12 (yes/no).              |
| Others      | Images from SDSS, Palomar-Quest, DSS, 2MASS. |
| Followed    | P60 follow up.                               |
| Last        | Last data update.                            |
| LC          | Curren CSS lightcurve.                       |
| FC          | Finding chart (yes/no).                      |
| Class       | Transient classification.                    |


In hdu 1, you can find a table that contains information to identify the images by sequence, date, MJD, Field ID, observation number in the sequence, or cutout.

| Table of Content HDU:1 (Table) | Description                                                                |
|-------------------------|-----------------------------------------------------------------------------------|
| HDU_Ext                 | Extension number of the image in the fits file.                                   |
| Sequence                | Stands for the sequence (or set number).                                          |
| Date                    | Date of observation in YYMMMDD format.                                            |
| MJD                     | Modified Julian Date.                                                             |
| Field_ID                | Field identifier.                                                                 |
| Obs_In_Seq              | Refers to the observation’s number in the sequence.                               |
| Cutout                  | The cutout matrix location. Each cutout covers an area of ABOUT 5 x 5 arcminutes. |

## Non-Transients Objects

For non-Transients objects, you can find in the fits images' headers the next information: 


| Header Dict | Description                                  |
|-------------|----------------------------------------------|
| CRTS_ID     | Catalina Real-time Transient Survey  ID from was extrated the non-transient object.     |
| N_Images    | Total number of images for this non-Transient object.     |
| RA_(J2000)  | Right Ascension (degrees).                   |
| Dec_(J2000) | Declination (degrees).                       |
| Img_Ref    | Image of reference where was identified the non-transient object.     |

Also, in hdu 1, you can find a table that contains information to identify the images of non-transients by MJD, date, field id, or cutout.

| Table of Content HDU:1 (Table) | Description                                                                |
|-------------------------|-----------------------------------------------------------------------------------|
| HDU_Ext                 | Extension number of the image in the fits file.                                   |
| MJD                     | Modified Julian Date.                                                             |
| Date                    | Date of observation in YYMMMDD format.                                            |
| Field_ID                | Field identifier.                                                                 |
| Cutout                  | The cutout matrix location. Each cutout covers an area of ABOUT 5 x 5 arcminutes. |


# How to read the dataset?

An example of how to read the data set is [here](../master/Read_dataset.ipynb).