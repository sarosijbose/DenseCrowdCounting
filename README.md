# Dense Crowd Counting
IoT course capstone project

## Methodology
The following features must be included in the system that is created.

1. Read the video's frames in order.
2. On the input frame, sketch the reference line of your choice.
3. Utilizing an object detection approach, find the persons.
4. Highlight the found individual's centroid.
5. Keep tabs on the centroid that was marked.
6. Determine the centroid's movement direction (whether it is moving upwards or downwards).
7. Count how many individuals enter or exit a reference line.
8. Increase or decrease the counter based on the counting.

## Requirements
Since the deep learning project has few dependencies, we can build it locally.
Putting in the libraries

```py 
pip install numpy
pip install opencv-python==3.4.2.16 
```
The Centroidtracker Python file is then required.

Here, we'll utilize the YOLO v3 model to find the individual in the frame. Therefore, in addition to downloading the coco classes (coco.names file), we also need to download the YOLO v3 weights and YOLO v3 settings files.
