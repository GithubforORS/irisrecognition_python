# irisrecognition_python
this is a python code for iris feature extraction and matching using ml algorithms
segmentation:

Canny Edge Detector:

 The Canny edge detector is often used as a preprocessing step in iris segmentation. It helps in identifying the edges of the iris and pupil regions. By detecting edges, you create a binary image where the edges are highlighted, making it easier to find the boundary between the iris and the pupil.

Hough Transform:

 The Hough Transform is used to detect circular shapes, like the iris and pupil, in the edge-detected image produced by the Canny edge detector. It helps in precisely locating the circles' parameters (center coordinates and radii).

By combining these two techniques, you enhance the accuracy of iris segmentation. The Canny edge detector highlights the edges, and the Hough Transform helps precisely locate circular boundaries.


Normalisation:

The Daugman Rubber Sheet Model, a technique in iris normalization, facilitates the standardization of iris texture patterns for accurate recognition.After detecting the pupil's center and radius, alongside locating the iris boundary using segmentation techniques,we will calculate polar coordinates for each cartesian coordinates along the iris boundary . A normalized template is created.using interpolation techniques normalized template retains important texture patterns from the original iris.This process compensates for variations in pupil dilation, eyelid occlusion, and other factors that can affect the appearance of the iris in different images.

