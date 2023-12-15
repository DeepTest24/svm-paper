# About

This repository holds implementation and evaluation results of NSGA-II-SVM presented in the paper with the title submitted at DeepTest@ICSE24: "Guiding the Search Towards Failure-Inducing Test Inputs Using
Support Vector Machines".

## Algorithm

The reflection study has been conducted with the support of the testing framework [OpenSBT](https://git.fortiss.org/opensbt/opensbt-core).
The algorithm is implemented using OpenSBT. The implementation is provided [here](algorithm/kernel_svm.py).

## Results Combined
The *Hypervolume/General Distance/Spread*analysis results after 10 runs are available here: 
<img src="subplots_combined.png" alt="results_10_runs" width="600"/>

The detailed *Hypervolume* analysis results are available here: [HV](/hv/)

NSGAII-SVM         |  NSGAII-DT |   RS
:-------------------------:|:-------------------------:|:-------------------------:
<img src="hv/hv_global_combined_NSGA-II.png" alt="HV" width="600"/>  |  <img src="hv/hv_global_combined_NSGA-II-DT.png" alt="HV" width="600"/>
| X
The *Spread* analysis results are available here: [Spread](/sp/) 

NSGAII-SVM         |  NSGAII-DT |   RS
:-------------------------:|:-------------------------:|:-------------------------:
<img src="sp/sp_combined_NSGA-II.png" alt="SP" width="600"/> |  <img src="sp/sp_combined_NSGA-II-DT.png" alt="SP" width="600"/>  | <img src="sp/sp_combined_NSGA-II-DT.png" alt="SP" width="600"/>

The *General Distance* analysis results are available here: [GD](/gd/) 

NSGAII-SVM         |  NSGAII-DT |   RS
:-------------------------:|:-------------------------:|:-------------------------:
<img src="gd/gd_combined_NSGA-II.png" alt="GD" width="600"/> | <img src="gd/gd_combined_NSGA-II-DT.png" alt="GD" width="600"/> | <img src="sp/sp_combined_NSGA-II-DT.png" alt="SP" width="600"/>


## Results Single Runs

The results of each single run of NSGAII-SVM are available here: [Single Runs NSGAII-SVM](NSGA-II/)

The results of each single run of NSGAII-DT are available here: [Single Runs NSGAII-DT](NSGA-II-DT/)

The results of each single run of NSGAII-RS are available here: [Single Runs RS](RS/)
