# A MULTI-TASK DEEP LEARNING FRAMEWORK FOR BUILDING FOOTPRINT SEGMENTATION
This repository contains the code for the paper [Land Use and Land Cover Mapping Using Deep Learning Based Segmentation Approaches and VHR Worldview-3 Images]([PLACEHOLDER])

Framework
---------------------
The framework of this study is detailed as follow. 

![alt text](flowchart_lulc.png)

Outputs
---------------------
![alt text](outputs_0.png)
![alt text](outputs_1.png)
![alt text](outputs_2.png)

Dataset and Weights
---------------------
| Dataset            | No of Parameters | F-1 Score | Weights |
|:--------------------------:|:------------------:|-------------------------:|-------------------------:|
|Aksu                       | 8 Batch-Size                | **0,564**                      | [Timm-resnest200e.pth](https://drive.google.com/drive/folders/146HRDz-075PTf-pyUQO-1ZrU4X1UQ5L2)                   |
|Kestel                         | 16 Batch-Size                 | 0,525                      | [Inceptionv4.pth](https://drive.google.com/drive/folders/146HRDz-075PTf-pyUQO-1ZrU4X1UQ5L2)                 |
|Aksu + Kestel Combined                       | 16 Batch-Size                 | 0,511                     | [Densenet201.pth](https://drive.google.com/drive/folders/146HRDz-075PTf-pyUQO-1ZrU4X1UQ5L2)   


System-specific notes
---------------------
The code was implemented in Python(3.8) and PyTroch(1.14.0) on Windows OS. The *segmentation models pytorch* library is used as a baseline for implementation. Apart from main data science libraries, RS-specific libraries such as GDAL, rasterio, and tifffile are also required.


Citation
---------------------
Please kindly cite our paper if this code and the dataset used in the study is useful for your research.

[PLACEHOLDER]
