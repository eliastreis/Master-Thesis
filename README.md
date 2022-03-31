# 📖 Master-Thesis
This repository includes materials for the **arena-bench** master thesis.
> You can find a PDF version of the thesis [here]

## Data collection
To comprehend the benefit of realistic robot-modeling in dynamic real-live like scenarios, extensive benchmarking has been conducted. 
- Click [here](https://github.com/ignc-research/arena-rosnav-3D/tree/f3e92aafa5e933088e9582936f114a5fb77935ac) to find the **arena-rosnav-3D** github repo at the time of data-collection
- Click [here](https://github.com/ignc-research/arena-rosnav/tree/de8b4277f1f19dec64e7cc2346cfdc93d68b36de) to find the **arena-rosnav** github repo at the time of data-collection
- Find in folder [scenarios](data_collection/data) the scenarios written for the data collection
- Find in folder [evals](data_collection/evals) the eval scripts to recreate the data-collection run
- Find in folder [data](data_collection/data) the csv-recording of the simulation runs
---

## Results
This folder contains a comprehensive list of evaluation results.
- Find in Folder [2D3D](results/2D3D) comparisons between the 2D Flatland simulator and the 3D Gazebo simulator
- Find in Folder [emergency-break](results/emergency_break) the evaluations regarding the emergency break systems with mobile robots in a 3D environment
- Find in Folder [comparison-local-planner](results/comparison-local-planner/) the results of comparing the behavior of the local planner with different robots according to the probability of collision-free navigation.
