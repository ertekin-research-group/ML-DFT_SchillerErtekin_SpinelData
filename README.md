# ML-DFT_SchillerErtekin_SpinelData

### Data repository for the article:

[A Combined DFT/Machine Learning Framework for Materials Discovery: Application to Spinels and Assessment of Search Completeness and Efficiency](https://chemrxiv.org/articles/preprint/A_Combined_DFT_Machine_Learning_Framework_for_Materials_Discovery_Application_to_Spinels_and_Assessment_of_Search_Completeness_and_Efficiency/13070549/1)

by Joshua Schiller and Elif Ertekin

### Files:

#### SpinelHullDistances.json

Contains distance to formation energy convex hull for all compounds calculated across all runs. Energies are adjusted according to Materials Project compatibility requirements. Energies represent the lower energy state between normal and proxy-orderered inverse comfiguration for each stoichiometry. 

JSON Format: {Stoichiometry: Hull Distance (eV/atom)}

#### top_predictions_all.xlsx

Contains top predictions of candidate compounds and their associated model scores for the final iteration of the reinforcement learning procedure.
