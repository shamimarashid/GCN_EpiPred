# GCN_EpiPred

This code was developed using python 3.9, on an Ubuntu 22.04.3 LTS operating system. 

Dependencies:

1. Numpy 1.12.5
2. torch Geometric 2.1.0
3. torch 1.12.1
4. Pandas 1.1.5 # for data loading 
5. RDKit 2022.09.1
6. sklearn 1.1.1
7. mitdeeplearning  
8. IPython 8.4.0      
9. tqdm 4.64.0

Finally, layers.py from https://github.com/inyeoplee77/SAGPool/blob/master/layers.py was used for the SAG Pooling layer.
GCN_EpiPred.ipynb also works on MacOS, although dependencies' versions might differ from the list above. Some modules such as mitdeeplearning, IPython and tqdm are for display of loss curve plots and iteration progress bars, and can be left out (comment out their lines). 

If the code or poster of GCN_EpiPred were useful in your work, please cite the abstract or link directly to this repository. Thanks!

If the CoV-AbDab_310.csv data was useful, please cite _PESI: Paratope-Epitope Set Interaction for SARS-CoV-2 Neutralization Prediction_ by
Zhang Wan, Zhuoyi Lin, Shamima Rashid, Shaun Yue-Hao Ng, Rui Yin, Jayavelu Senthilnath, and Chee-Keong Kwoh. Proceedings of the IEEE Conference in Bioinformatics and Biomedicine (BIBM) 2023. 
