# Extended-Featureset-Adaptation-PCA

This repository contains the source code to reproduce the results of paper:
- `Karn, Rupesh Raj, and Ibrahim Abe M. Elfadel. "Hardware/Software Co-acceleration of Progressive Learning under Feature Dimension Variation." In 2022 International Conference on Electrical and Computing Technologies and Applications (ICECTA), pp. 275-278. IEEE, 2022`.
- `Karn, Rupesh Raj, and Ibrahim Abe M. Elfadel. "Progressive Learning under Feature Dimension Variations with Application to Network Cyber Security" (Under Review)`.

This work uses synaptic weight consolidation methodology implemented in 

    https://github.com/ganguli-lab/pathint
    
    Install the python libraries mentioned there.
    
    Each of the jupyter notebook file shows implementation for the respective dataset: UNSW, AWID, MNIST. To run the code, please perform following steps:
    1. git clone https://github.com/ganguli-lab/pathint
    2. cd pathint/fig_split_mnist/
    3. Copy all the three ipynb files in "pathint/fig_split_mnist/" directory.

UNSW-NB15 dataset can be downloaded from

    https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/

    Download the UNSW_NB15_training-set.csv and UNSW_NB15_testing-set.csv files.
    
AWID Dataset can be downloaded from 

    http://icsdweb.aegean.gr/awid/download.html 
    
    Download the AWID-ATK-R-Trn and AWID-ATK-R-Tst files. 
    
    Description links:     
    http://icsdweb.aegean.gr/awid/features.html 
    http://icsdweb.aegean.gr/awid/attributes.html
    http://icsdweb.aegean.gr/awid/draft-Intrusion-Detection-in-802-11-Networks-Empirical-Evaluation-of-Threats-and-a-Public-Dataset.pdf
    
MNIST dataset can be fetched from python Keras.
