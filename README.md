# YOLO_object_detection_opencv_python


Object detection and Classification is successfully implemented using python and OpenCV

## Operating System used
   Window 10 Home 32 bit
   Ram : 2 GB
   Processor: intel pentium cpu g2030 @ 3.00 ghz 

## Versions used
 1. python 3.6.5
 2. opencv 3.4.4

## Third party libraries used
1. numpy (for mathematical tasks)
2. requests (for video input from a url in my case via wifi using ipcam android app)

## Steps for recognisation
1. getting images of objects to be detected via android mobile camera using ipcam android app
2. Loading the Required yolo files

Note : download and put the required "yolov3.weights" file in the working directory from [here](https://pjreddie.com/media/files/yolov3.weights).

3. feeding the images to the classifier
4. getting the output layer and detected objects
5. making rectangle and labels on the objects of the image

## Conclusion and What i learned
1. it takes 4-5 seconds to classify a single image on my pc 
2. accuracy is very good. (i had set in my code to labels objects over 50 percent accuracy)
