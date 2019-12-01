# Python-Mask-R-CNN
Object detectors such as YOLO, SSDs, and Faster R-CNNs are only capable of producing bounding box coordinates of an object in an image — they tell us nothing about the actual shape of the object itself.

Using Mask R-CNN we can generate pixel-wise masks for each object in an image, thereby allowing us to segment the foreground object from the background.

Furthermore, Mask R-CNNs enable us to segment complex objects and shapes from images which traditional computer vision algorithms would not enable us to do.

the code is trained on coco dataset with 90 classes.

Interesting to see that with an image of 2 persons that has mirror reflection , the model predicted 5 persons with bounding boxes. Working on fixing this issue
