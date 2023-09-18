# ALBA
Active Learning for Binding Affinity Prediction Code Repository

The data is from DUDE (Database of Useful Decoys: Enhanced) website. The link is https://dude.docking.org/subsets/all

Five subsets of targets are used in this study, which are: AA2AR, ADA17, DPP4, MK14, SRC.

The code for preprocessing the data is in folder "preprocess_data". The code for active learning workflow is in folder "al_workflow".


Require: 
python >= 3.6
rdkit   
datamol   
pandas
torch_geometric
