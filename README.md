# Objective
For good efficiency, fast, reliable and smooth operation of any process we need a failure free operation. Identification of fault, its detection, protection and fault analysis are necessary to prevent unexpected events in solar photovoltaic (PV) systems. This project aims at defect inspection of solar modules in electroluminescence (EL) images. Various types of defects in solar cells as shown below:
![ImG of defects](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/Screenshot%20from%202020-08-26%2022-44-29.png)

# Methodlogy
A VGG-19 architecture was used for the task at hand, which was followed by a fully connected layer. VGG-19 is a variant of VGG model containing 19 trainable layers and trained on imageNet dataset. Using transfer learning, the pretrained VGG-19 was further tweaked to improve accuracy on our EL image dataset.

# Dataset 
A dataset of 280 solar modules was used. From the large solar modules, individual solar cells were extracted and pre-processed. A total of 2788 images consisting good cells and defective cells. The dataset was further divided into 1952 and 836 images as train and validation dataset.
###### EL Image of solar module:
![ImG of modules](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/sample_input1.jpg)

###### EL Image of procesed solar cells:
Processed solar cell 1 | Processed solar cell 2
------------ | -------------
![ImG of processed image](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/M10_IMG19.jpg) | ![ImG of processed image2](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/M10_IMG9.jpg) 

# Result

###### Testing Accuracy:
![ImG of modules](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/Screenshot%20from%202020-08-26%2022-55-15.png)
###### Sample output:
![ImG of modules](https://github.com/AbhinavKSeth/Defective-Solar-Cell/blob/master/Sample_output.png)


