# Defective-Solar-Cell
This project aims at identifying defective solar modules in electroluminescence (EL)images.
In general, defects in solar modules can be classified into two categories (1) intrinsic deficiencies due to material properties such as crystal grain boundaries and dislocations, and (2) process-induced extrinsic defects such as microcracks and breaks, which reduce the overall module efficiency over time.
A VGG-19 cnn model was used for the task at hand.To train the data, we had EL images of about 280 solar modules, from which about 700 individual solar cells have been extracted with after data augmentation rounded up to about 2800 images, which was further divided into 1900 images as training dataset and 800 testing data.
