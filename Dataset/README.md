# Experiment Data

The data for this project are collected and organized using [UXF](https://immersivecognition.com/unity-experiment-framework/).

## Folder structure

The folder structure is as follows:

- `/<Participant ID>`: All data for a single participant
    - `/<Session ID>`: (Used to split the experimental conditions)
        - `/session_info`: The general data
            - `log.csv`: The console log of the Unity instance (unused in this experiment)
            - `participant_details.csv`: Demographics gathered at the start of the experiment (unused in this experiment)
            - `settings.json`: The (UXF) settings file used for the experiment (unused in this experiment)
        - `/trackers`: All tracker data
            - `camera_movement_T001.csv`: Tracked position of the HMD (to which the player camera was attached)
            - `controller_(left)_movement_T001.csv`: Tracked position of the left controller (held by the participant)
            - `controller_(right)_movement_T001.csv`: Tracked position of the right controller (held by the participant)
            - `hip_movement_T001.csv`: Tracked position of the hip tracker (attached to the participant)
            - `left_foot_movement_T001.csv`: Tracked position of the left foot tracker (attached to the participant)
            - `right_foot_movement_T001.csv`: Tracked position of the right foot tracker (attached to the participant)
        - `trial_results.csv`: Not used in this experiment
- `questionnaires.xlsx`: All questionnaire data.
- `targetlocations.csv`: The locations of the targets in the Unity scene

## Data dictionary

In the datasets, the following variable names have been used:

- `time`: Timestamp of the recorded row in seconds
- `pos_x`: The x position in meters
- `pos_y`: The y position in meters
- `pos_z`: The z position in meters
- `rot_x`: The x (Euler) rotation in degrees 
- `rot_y`: The y (Euler) rotation in degrees 
- `rot_z`: The z (Euler) rotation in degrees  