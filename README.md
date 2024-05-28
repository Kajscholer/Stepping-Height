# Influence of Virtual Reality Body Representations on Stepping Height

## Data
The raw data can be found within the 'data' folder. Here you can find 12 individual participant ID's. Within each of these folders, there are 3 session ID's, which represent the trial number. Within these folders, there is the 'trackers' folder, which contains the different tracking data. The ones that are used for this research include "left_foot_movement_T001" and "right_foot_movement_T001", which correspond to the tracked position of the left and right foot. The rest can be disregarded, as they are trackers of other body parts. Additionally, within the session ID folder, there is also a "trial_results", which can also be disregarded, as it will not be used within this study. Within the "left_foot_movement_T001" and "right_foot_movement_T001" datasets, there are various variables. In this study, only the 'time', 'pos_x', 'pos_y' and 'pos_z' are taken into account. They represent the timestamp in seconds and x, y, and z position in meters.

## Data processing
The file "DataProcessing.Rmd" entails the main data analysis code, which is written in R. 

### How to run the script
Before running the script, you must download R and RStudio. The following link provides you with the details on how to install them: https://rstudio-education.github.io/hopr/starting.html

Then script can be opened through RStudio. Here you should press 'Run Document'. This will then tell you to install the necessary libraries, which will take a couple of minutes to download. Once they all have been downloaded, you can press 'Run Document' again.

It should be noted that most of this code was written by van den Berg [[1]](#1). The code that has been written for this specific research can be found in section "Engineering Research Code", which plot the results shown in the report.

## References 
<a id="1">[1]</a> 
A. van den Berg, B. de Vries, Z. Breedveld, A. Mierlo, M. Tijhuis, and
L. Marchal-Crespo, “Embodiment of virtual feet correlates with motor
performance in a target-stepping task: a pilot study,” Frontiers in Virtual
Reality, vol. 4, 07 2023