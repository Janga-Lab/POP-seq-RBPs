# predict_RBPs
predict_RBPs is a framework for predicting RNA-binding protein (RBPs) on Protein Occupancy Profile-Sequencing (POP-seq) data, where POP-seq is methedology for capturing nearly all RBP-RNA interactions, regardless of their identities and it doesn’t require crosslinking.  

# The following softwares and modules should be installed before using predict_RBP

python 3.6.10

numpy 1.18.1

pandas 1.0.1

sklearn 0.22.2.post1

tensorflow 2.0.0

keras 2.3.1 (using Tensorflow backend)

# Running  predict_RBP:

In order to run  predict_RBP, the user has to do the following:

1- Ensure that Encode data file that that identifies the RBPs on the CLIP-seq data a specific cell line is in the same path where  main.py file exists.

2- Ensure that Pop-seq data file for the same cell line on which the RBPs will be predicted/identified  is in the same path where  main.py file exists.

2- Run the following python command:

python main.py 

# Note:
The default Machine Learning model used in predict_RPBs framework is the Random Forest (RF) with RNA sequence embedding.
