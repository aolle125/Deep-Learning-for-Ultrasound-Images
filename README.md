# Deep-Learning-for-Ultrasound-Images

The ability to obtain graded proportional control is limited by the fundamental challenges with sEMG amplitude resolution and low signal-to-noise
Ultrasound imaging provides a non-invasive sensing modality that can spatially resolve individual muscles, including those deep inside the tissue, and detect dynamic activity within different functional compartments in real-time.

Sonomyography-based strategy measures mechanical muscle deformation directly with ultrasound and uses the extracted signals to proportionally control the position of an end-effector
Prediction of the type of motion and the completion level from the video sequences of Sonomyography data using Deep Learning
Improvement of prediction accuracy at earlier completion levels for better proportional control


There are 9 motions in total and each motion had 5 trials taken from two test subjects and have completion level values from 0-100
I have performed 3 experiments:

Using VGG-16 architecture (Fine Tuned and Off the Shelf)

Using ResNet-34 architecture (Fine Tuned and Off the Shelf)

Using a Off the Shelf ResNet-34 for prediction of motion name with Additional Fully Connected Layers

Data Pre-processing

Converting the Images to 227 × 227 × 3

Dividing the data into train/validation/test sets

Label Encoding


Data Augmentation
Resizing

Center Crop

Horizontal and Vertical Flipping

Rotation

Normalization


