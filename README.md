# YOLOv5 Object Detection for RarePlanes Tutorial

This repo contains three notebook tutorials in which you create a custom class using the RarePlanes data set, train a YOLOv5 model, perform inferences on the test set, and then evaluate performace. 

### How to use this repo: 

You can either access the tutorial pipeline hosted on AWS by accessing the AMI [here](http://example.com/) or reproduce the enviornment using your own GPUs by cloning this repository

A. AMI/EC2

For the AMI, all the relevant data and packages have been downloaded so you should easily . 

1. Spin up the AMI instance from [here](http://example.com/)
2. Navigate to the directory `/home/ubuntu/src/yolo_planes/yolov5/`
3. Launch the jupyter lab using `jupyter lab --pi=0.0.0.0`
4. Open a browser and insert the EC2 ip into the address bar; it should look like this `ec2-3-235-146-223.compute-1.amazonaws.com:8888`
5. The password for the jupyter lab is `yoloplanes`
6. Open the notebook titled `1_yolo_start.ipynb`

B. On your own machine 

1. Clone this repository 
2. Download the data from [here](https://www.cosmiqworks.org/rareplanes/). You will only need the real data for this tutorial 
3. 




This ML pipeline uses a modified implementation of the YOLOv5 implementation found [here](https://github.com/ultralytics/yolov5). The full RarePlanes dataset can be found [here](https://www.cosmiqworks.org/rareplanes/) and helper functions for the dataset can be found [here](https://github.com/aireveries/RarePlanes). 

If you have any questions or errors, please don't hesitate to post an issue or contact me [here](achadda@iqt.org). 

