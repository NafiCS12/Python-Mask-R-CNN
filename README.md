# Python-Mask-R-CNN
Using Mask R-CNN we can generate pixel-wise masks for each object in an image, thereby allowing us to segment the foreground object from the background.

Furthermore, Mask R-CNNs enable us to segment complex objects and shapes from images which traditional computer vision algorithms would not enable us to do.

the code is trained on coco dataset with 90 classes.

Interesting to see that with an image of 2 persons that has mirror reflection , the model predicted 5 persons with bounding boxes. Working on fixing this issue
