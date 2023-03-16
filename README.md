# Object_Detection_yolo5s

### Problem Statement 

* The objective of the task is to count the number of small, medium and large pipes from the given video footage.
* The given footage is taken from a camera mounted on top of a mobile base. The mobile base is travelling across a warehouse inside a simulation world. There are several pipes of various sizes(small, medium and large) kept inside the warehouse.
* This task is based on a real-world application of computer vision in robotics, where robots are used in environments like warehouses for surveillience and management of goods.
* To achieve this task, you are supposed to devise a method to count the pipes belonging to various sizes.

### Solution
1. Extracted frames from given footage using ffmpeg to use as training set object detection model
2. Used roboflow to create training,testing and validation dataset for creating a custom object detector
3. Clone yolov5 repository and dataset from robolflow using your api key in form of data.yaml file for training your custom object detector
4. Used yolov5s model and experimented with various parametors and confidance value to get expected result and got custom object detector which detect pipes in any given image or video with high accuracy
5. Made changes in detect.py to keep track of pipes of different size and print the output in video

### Input Video

https://user-images.githubusercontent.com/103204383/211204827-404687ed-99e0-4456-ac56-2546e9da525a.mp4


### Output Video

https://user-images.githubusercontent.com/103204383/211204782-d194d8d7-9f51-49eb-8d3d-05fa55687c05.mp4




