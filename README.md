## Simple Image Enhacement-example
### A Python program implementing image filtering features

The program implements some common basic methods to apply image enhancement features including rescaling, contrast, denoising and threshold on images in the original folder in order to make the text of pictures clearer using image proccessing libraries such as :
- Scikit-image
- OpenCV
- PIL

the order of appllying each filter on images is cosidered to have better performance.
<br/>

### note 
you can replace the content of the origin folder with your own pictures. 
<br/>

</br>




## Simple Image Classification
### A Python program extracting image features with skimage library and implmenting classification to detect category of each flower

a set of a hundred flower images are collected and arranged into K categories then 
+ made a feature vector per image and added category of each image at the end of the feature vector
+ the dataset is divided into train and test
+ the classification is done by supervised learning using RandomForestClassifier form sklearn library
+ the result is determined with test data
