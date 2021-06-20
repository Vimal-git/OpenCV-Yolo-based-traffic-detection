# General Description
* This project processes an image frame of video captured by a camera on moving vehicle to classify and draw bounding box around vehicles in the field of view.
* The details of bounding boxes are stored in a data structure. 
* This project was developed from code and instructions provided by Dr Andreas Haja as part of Udacity's Sensor Fusion Nano Degree program.

## Running the project
* Download the Project folder `OpenCV_Yolov3_Application`.
* Download yolov3.weights from [here](https://pjreddie.com/media/files/yolov3.weights)
* Copy this to `OpenCV_Yolov3_Application/dat/yolo`
* Change the `referencePath` variable at line 16 of `detect_objects_2.cpp` to appropriate path in your system.
* Change directory to `OpenCV_Yolov3_Application/` and run `mkdir build`
* run `cd build`
* run `cmake .. && make`
* run `./detect_objects`
* Press `Ctrl+C` to stop