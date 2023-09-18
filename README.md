# ALBA
Active Learning for Binding Affinity Prediction Code Repository

The data is from DUDE (Database of Useful Decoys: Enhanced) website. The link is https://dude.docking.org/subsets/all

Five subsets of targets are used in this study, which are: AA2AR, ADA17, DPP4, MK14, SRC.

The "preprocess_data" folder contains the preprocessing code for the data, as well as the export files for the training and test sets. 

The "al_workflow" folder contains the entire active learning pipeline with two QSAR models (ECFP and GNN), two uncertainty estimation strategies (Dropout and Ensemble). In addition, the baseline models for ECFP and GNN and the Random Selection are also included.

The "result" folder stores the results of the data generated from  folder "al_workflow".


Require: 
python >= 3.6
rdkit   
datamol   
pandas
torch_geometric
