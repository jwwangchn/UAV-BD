In this paper, we propose a new dataset and benchmark for low altitude UAV object detection, aiming to find and localize waste plastic bottles in the wild, as well as to inspire the development of object detection models to be capable of detecting small and transparent objects. To this end, we collect 25,407 UAV images of bottles with various kinds of backgrounds. Unlike traditional horizontal bounding box based annotation methods, we use the oriented bounding box to accurately and compactly annotate the bottles, which provides more detailed information for subsequent robotic grasping. The fully annotated images contain 34,791 bottles, each of which is annotated by an arbitrary (5 d.o.f.) quadrilateral. To build a baseline for bottle detection, we evaluate several state-of-the-art object detection algorithms on our UAV-Bottle Dataset (UAV-BD), such as Faster R-CNN, SSD, YOLOv2 and RRPN. We also present an analysis of the dataset along with baseline approaches. Both the dataset and benchmark are made publicly available to the vision community on our website to advance research in the area of object detection from UAVs.

## Annotation format
In the dataset, each instance's location is annotated by a quadrilateral bounding boxes, which can be denoted as <a href="https://www.codecogs.com/eqnedit.php?latex=(c_x,&space;c_y,&space;w,&space;h,&space;\theta)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(c_x,&space;c_y,&space;w,&space;h,&space;\theta)" title="(c_x, c_y, w, h, \theta)" /></a>

## Development kit

The [Development kit]() provide the following function
- Load and visulize the data.
- Evaluate the result.

## Download dataset
You can download UAV-BD from Google Drive. The current version of dataset is 1.0.0.