# JGR_Onodera2023_Catalog
## Overview
This repository includes the catalog related to Martian convective vortices observed by NASA's InSight mission.
The detailed description is made in the JGR Planet paper entitled "Systematic catalog of Martian convective vortices observed by InSight" by Onodera et al.
When you use the information in the catalog, please refer the following citation.

Onodera, K. et al. (2023), Systematic catalog of Martian convective vortices observed by InSight, JGR Planets, ***, doi***.

## Files
### InSight_CV_Catalog.pickle
It includes all estimated parameters presented by Onodera et al. (2023).
 
### Dataset
Since the total file size is too big to upload here, please send a request to "onodera(at)eri.u-tokyo.ac.jp" if you need the dataset.
Or, you may retrieve the data by yourself, referring to the time information in the catalog.
The sample code for downloading the InSight data is available at the following link:
https://researchmap.jp/blogs/blog_entries/view/809479/d29ec3b7f0fdd5a15a3be04ec97dc762?frame_id=1470639

#### PS: 20 min long pressure data centered at the maximum pressure drop time (LMST, Pressure). 
#### VBB_ACC: 20 min long pressure data centered at the maximum pressure drop time (LMST, Z comp. , N comp., E comp.).
#### WSpeed_WDir_ATemp_calib: 20 min long calibrated wind & air temperature data centered at the maximum pressure drop time (LMST, Wind speed , Wind direction, Air temperature).
The first character in each file corresponds to the ID number included in the catalog file (InSight_CV_Catalog.pickle). 
All files are in csv format including time in Local Mean True Time in sol, respective observation records.
If a number is missing, that means the corresponding data were not available on that sol (at least with the sampling rate we focused on in our paper).
