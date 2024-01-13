
indian currency/notes - v4 2023-02-24 12:45pm
==============================

This dataset was exported via roboflow.com on July 19, 2023 at 12:38 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 6259 images.
Currency are annotated in Tensorflow TFRecord (raccoon) format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 480x480 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -26 and +26 degrees
* Random shear of between -31° to +31° horizontally and -18° to +18° vertically
* Random exposure adjustment of between -26 and +26 percent

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Salt and pepper noise was applied to 3 percent of pixels


