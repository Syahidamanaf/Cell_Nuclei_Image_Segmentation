# CELL NUCLEI IMAGE SEGMENTATION USING U-NET
 
## DATASET

Description
This dataset contains a large number of segmented nuclei images. The images were acquired under a variety of conditions and vary in the cell type, magnification, and imaging modality (brightfield vs. fluorescence). The dataset is designed to challenge an algorithm's ability to generalize across these variations.

Within this dataset zip file contain test set folder and train set folder. In each folder, there are 2 subfolders contain :

1. images which has the image file.
2. masks which has the segmented masks of each nucleus. 

References : Kaggle 2018 Data Science Bowl
The image dataset can be downloaded on Kaggle website @ https://www.kaggle.com/competitions/data-science-bowl-2018/data


## GOOGLE COLAB

The purpose of this project is to identify the cell nuclei from images using the image segmentation method.  Google colab is used for this image segmentation project with the application of Numpy, OpenCV, and Tensorflow Keras.

## MODEL PREDICTION AND RESULT

This project is created by using U-Net Convolutional Network for fast and precise segmentation of biomedical images. The network consists of 2 paths with are contracting path and expansive path which result to u-shaped architecture. 

The model was trained with 30 epochs with batch size of 16 and produced training accuracy of 0.9796 and validation accuracy of 0.9649. The accuracy and loss later is obtained using test set. The result shows the high accuracy which is 0.9627. On the other hand, the loss on test set is 0.10135. Thus, it can be concluded that this model produced high accuracy hence are suitable to be used for cell image segmentation.



