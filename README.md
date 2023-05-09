# Multi-Cancer Identification and Segmentation


<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/9fa0b60f-52b5-4f36-9164-7b4d117b6555"/>
</p>

<p align="center">
Proposed System Architecture
</p>

The project aims to be able to identify the presence of tumors in brain and breast scans. The first step of the project is to classify whether a given scan is a brain or breast scan. After determing the type of the scan, we classify whether a tumor is presnet or not, If a tumor is present it is segmented and displayed as a binary image.


## Project Aims
* Apply image classification to classify each image as a brain scan or a breast scan and then determine if the scan is normal or if it has a tumor.
* Apply image segmentation to determine the exact location of the infected area.
* Determine the width and height of the tumor in the scan if it exists.

## Data Set
The dataset for this project can be found [Here](https://drive.google.com/file/d/1z-qAHlyhfeCCTdKnwvC9iAV2lOEXL_X3/view)
Data Set Samples
<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/9682fd2e-c1d1-4a95-b97f-b0642033a1c4"/>
</p>
<p align="center">
Brain Scan with Correpsonding Mask
</p>

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/098cf3fd-eaeb-492d-b9d7-70391858ad0b"/>
</p>
<p align="center">
Breast Scan with Correpsonding Mask
</p>

## Results
Below is breif description of the results of models used

### Brain/Breast Classifier
* Model: VGG16-Based Classifier
* Test Loss: 0.0000
* Test Accuracy: 1.0000
* Test Precision: 1.0000
* Test Recall: 1.0000
* Test F1 Score: 1.0000
<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/6fd15800-6021-4e33-b7e7-9f8e9d4a2f1c"/>
</p>
<p align="center">
Brain / Breast Classifier Results
</p>





### Brain Tumor Classifier
* Model: VGG16-Based Classifier
* Test Loss: 0.189
* Test Accuracy: 0.935
* Test Precision: 0.93
* Test Recall: 0.939
* Test F1 Score: 0.934

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/c25ef40d-e8e9-4de3-ad01-eb13c9cfa91b"/>
</p>
<p align="center">
Brain Tumor Classifier Results
</p>







### Breast Tumor Classifier
* Model: VGG16-Based Classifier
* Test Loss: 0.7698
* Test Accuracy: 0.6667
* Test Precision: 0.7197
* Test Recall: 0.6667
* Test F1 Score: 0.6694

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/169ce9ec-5abc-4858-93b2-857eec363198"/>
</p>
<p align="center">
Breast Tumor Classifier Results
</p>


### Brain Tumor Segmentation
* Test Loss = 0.112
* Test Dice Coef. = 0.607
* Test Mean IoU: 0.8336
* Test Precision: 0.8354
* Test Recall: 0.7926

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/385c193d-2175-4519-af12-1ee518eec74e"/>
</p>
<p align="center">
Brain Scans Segmentation Results
</p>



### Breast Tumor Segmentation
* Test Loss = 0.2063
* Test Dice Coef. = 0.768 
* Test Mean IoU: 0.624
* Test Precision: 0.806
* Test Recall: 0.734		

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/831ddbe1-b0c8-4a68-ada6-143a8b6011a1"/>
</p>
<p align="center">
Breast Scans Segmentation Results
</p>



### System Simulation
In this section it will be demonstrated how all of the models will work together

<p align="center">
  <img src="https://github.com/mkldhz/Multi-Cancer-Identification-and-Segmentation-Using-Brain-and-Breast-Scans/assets/61518213/201e2d32-8d89-478c-ae7e-e738f5c0b25f"/>
</p>
<p align="center">
System Simulation With Brain Scan
</p>








