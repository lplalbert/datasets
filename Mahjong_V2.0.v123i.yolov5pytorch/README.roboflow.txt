
Mahjong_V2.0 - v123 2022-09-23 12:35am
==============================

This dataset was exported via roboflow.com on September 22, 2022 at 4:39 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 18720 images.
Test are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Fill (with center crop))

The following augmentation was applied to create 3 versions of each source image:

The following transformations were applied to the bounding boxes of each image:
* Equal probability of one of the following 90-degree rotations: none, upside-down
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random brigthness adjustment of between -20 and +20 percent
* Random exposure adjustment of between -20 and +20 percent
* Random Gaussian blur of between 0 and 1.25 pixels
* Salt and pepper noise was applied to 1 percent of pixels


