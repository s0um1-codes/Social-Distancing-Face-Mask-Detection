# Social-Distancing-and-Face-Mask-Detection

This prototype detects social distancing in video footages given as input and can also perform real-time face mask detection using the device camera.
YOLO (You Only Look Once) framework is used to perform object detection and is trained on COCO dataset. The model identifies people in the frames, represents them in bounding boxes, computes the distance between all pairs and detects the violations based on the defined threshold. A CNN model used for performing face mask detection. It is trained with over 1000 images of people wearing masks and not wearing masks. It is tested with new faces using Python's computer vision package for video capture and processing and it peforms the detection displaying labels as 'safe' and 'not safe'.
