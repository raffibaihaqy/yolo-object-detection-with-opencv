# yolo-object-detection-with-opencv

1. download the model from 'https://pjreddie.com/darknet/yolo/' the name file is "yolov3.weights" move it or copy paste to folder 'yolo-coco' in yolo-object-detection-with-opencv project
2. in 'yolo_video.py' there's a variable 'vs = cv2.VideoCapture(rt)' you can change the 'rt' to '0' for your webcam laptop or '1' to external webcam
3. remember this is using CPU only not GPU because 'cv2.dnn.readNetFromDarknet' only support for CPU
4. if you want to use GPU you go to 'https://pjreddie.com/darknet/yolo/' and see the complete tutorial
5. run 'python yolo_video.py' for windows and 'python3 yolo_video.py' for mac or linux

THANKS...
