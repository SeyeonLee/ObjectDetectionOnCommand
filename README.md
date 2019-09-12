# ObjectDetectionOnCommand
Object Detection with transfer learning
## Project Overview

Welcome to Seyeon's Convolutional Neural Networks (CNN) Capstone project in the AI Nanodegree! This project will explore Object detection, which is a technology that detects objects, classify, and locate them in an image. 

This project will explore different CNN models using transfer learning, a method that uses a pre-trained neural network and adapt the model to perform different tasks with different dataset, and design a model that can find different objects and locate them with precision. PASCAL VOC (Visual Object Classes) 2012 dataset  will be in use of training models, and the model will be tested on the validation set provided by PASCAL VOC Challenge.

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/SeyeonLee/ObjectDetectionOnCommand.git
```

2. Download the [PASCAL VOC 2012 Training/Validation Data](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html#devkit). Unzip the folder and place it in the repo.
	- __Linux__: 
  	If you are using a Linux machine, you can refer to the website below.
  	https://www.pendrivelinux.com/how-to-open-a-tar-file-in-unix-or-linux/
  
  		- From the terminal, change to the directory where yourfile.tar has been downloaded.
 		- Type tar -xvf yourfile.tar to extract the file to the current directory.
  		- Or tar -C /myfolder -xvf yourfile.tar to extract to another directory
  
	- __Mac__: 
	Mac authomatically unzips .tar files.
  
	- __Windows__:  
	If you are using a Windows machine, you can use [WinZip](https://www.winzip.com/win/en/tar-file.html) to extract the folder.

3. Place all the folders and data in "/home/ubuntu/VocDevkit/" and run the ObjectDetectionOnCommand.ipynb.

