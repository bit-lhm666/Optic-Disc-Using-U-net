# Optic-Disc-Using-U-net

Folder structure:
'''
data/                                      includes all datasets, including HRF,RIM_ONE v2, DRISHTI_GS and sample_data datasets.
dual_IDG.py                                is used for data augmentation during training.
extract_data.py                            is used for extract data from original datasets.
imhandle.py                                is used for handling data and data preprocessing.
Optic_Disc test on sample_data.ipynb       is a notebbook for using data of all datasets  as training set to train the model and using the sample_data as the test set for testing.
Optic_Disc using RIM_ONE_v3.ipynb          is a notebook for using RIM_ONE_v3 dataset as training set and testing set to train and test model.
'''


# Environment
'''
Built with Python 3.7, Keras 2.3.1 with TensorFlow backend 2.0.0.
Must use the above versions of python libraries
'''


# Data
HDF5 datasets can downloaded from [this url](https://drive.google.com/drive/folders/13g62bhqN1JHJ2fky2Xy5avLbZ2YLMdwB).
please download HDF5 datasets and place data file.


# Citations
The repository refers to [optic-nerve-cnn](https://github.com/seva100/optic-nerve-cnn).

