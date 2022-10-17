
facets - v5 Dataset_for_Darknet
==============================

This dataset was exported via roboflow.com on October 15, 2022 at 8:49 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 774 images.
Part-of-face are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Random brigthness adjustment of between -42 and +42 percent
* Random Gaussian blur of between 0 and 2.75 pixels
* Salt and pepper noise was applied to 16 percent of pixels


