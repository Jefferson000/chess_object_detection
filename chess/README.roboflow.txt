
Chess Pieces - v19 augmented
==============================

This dataset was exported via roboflow.ai on February 18, 2021 at 11:24 PM GMT

It includes 2107 images.
Pieces are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 10 versions of each source image:
* 50% probability of horizontal flip
* Randomly crop between 0 and 5 percent of the image
* Random rotation of between -1 and +1 degrees
* Random shear of between -2° to +2° horizontally and -2° to +2° vertically
* Random brigthness adjustment of between -5 and +5 percent
* Random exposure adjustment of between -5 and +5 percent
* Random Gaussian blur of between 0 and 0.25 pixels


