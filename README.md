# Battery Management System Prediction for Electric Vehicles
### San Jose State University Master's Project from Aug 2021 - May 2022

---
##### This respository contains samples of my work done for my Master's Project at SJSU
---

### Project Description
The purpose of this group project of four people was to create a real time estimation of the state of charge (SoC) of an electric vehicle under dynamic operating conditions as well as forecast the plug-in duration for a full charge. The outcome should be a machine-learning forecasted battery management dashboard to be deployed in an online environment. 

### Datasets
##### Single Cell Nasa Battery Testing Dataset
https://data.nasa.gov/dataset/Li-ion-Battery-Aging-Datasets/uj5r-zjdb/data (B. Saha and K. Goebel, 2007)</br>
This dataset was collected by NASA Ames Prognostics Center of Excellence (PCoE) from tests conducted on the Li-ion 18650 rechargeable battery. According to the previous work done on this subject, single-cell battery data has been utilized to extrapolate SoC estimations. This is due to the proprietary nature of electric vehicle battery datasets that are available on the internet. The problem with using this dataset is that the dynamic aspect future operating conditions of an electric vehicle aren't considered.

##### Real Driving Cycles of Battery Pack Data
https://ieee-dataport.org/open-access/battery-and-heating-data-real-driving-cycles (Matthias Steinstraeter et al., 2020)</br>
This dataset was collected by a research team from the Technical University of Munich by collecting real data from a BMW I3 electric vehicle. This dataset contains environmental features such as weather and ambient temperature as well as battery and vehicle data. One of the issues that arise from using this rare dataset collected from an electric vehicle is that the data was collected only from one source and vehicle type. The predictions made may not apply to other vehicle models.


### Files in Repository
##### Electric Vehicle Battery Status Estimation.pdf
This file contains the 158-page final report for the project. This is the accumulaton of two semesters worth of research, planning, and execution by all group members. While I assisted in many areas, the work I specifically contributed is listed here.
 - Explored a variety of datasets as the Data Manager and cleaned, prepared, and transformed datasets
 - Contributed to the research for the project by finding relevant papers and analyzing past research
 - Heavily involved in the project management aspect by creating a project organization plan and a Gantt Chart for the project
 - Trained and optimized the Support Vector Regression model
 - Visualized the data statistics in Tableau as well as presenting the final results in Google Cloud Studio
 
##### Electric Vehicle Dataset - Data Prep.ipynb
This file contains and organized python notebook for the work I contributed towards data preparation for the battery pack dataset. This is a work sample and a portion of what I contributed to the coding aspect of the project as a whole.

### Future Work
This section is dedicated to listing out future submissions into GitHub as well as proposed improvements to predictions, models, or visualizations that I would be attempting solo.

- Import Tableau and Google Data Studio's visualizations and presentations
- Run predictions on the battery pack data to maintain the dynamic elements of the project
- Create a dashboard that responds to traffic patterns, incoming weather, or shifts in temperature
