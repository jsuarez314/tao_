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



| Table of Content HDU:1 (Table) | Description                                                                |
|-------------------------|-----------------------------------------------------------------------------------|
| HDU_Ext                 | Extension number of the image in the fits file.                                   |
| Sequence                | Stands for the sequence (or set number).                                          |
| Date                    | Date of observation in YYMMMDD format.                                            |
| MJD                     | Modified Julian Date.                                                             |
| Field_ID                | Field identifier.                                                                 |
| Obs_In_Seq              | Refers to the observation’s number in the sequence.                               |
| Cutout                  | The cutout matrix location. Each cutout covers an area of ABOUT 5 x 5 arcminutes. |