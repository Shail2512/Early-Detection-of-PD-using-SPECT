# Early-Detection-of-PD-using-SPECT
Early Detection of Parkinson's Disease is done using SPECT Image. The binary classification of PD patient and Healthy Control is implemented using CNN.

Dataset is taken from www.ppmi.org

Summary:\
  -Pre-processing of data includes normalization and binarization.\
  -The most significant image is obtained at the 40th slice.\
  -The label is converted generated using one-hot encoding.\
  -Keras Sequential model is impemented which also includes BatchNormalization. MaxPooling and Dropout.
