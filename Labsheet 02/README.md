### Goal
In this practical, you will learn how to convert images from one color-space to another, like BGR ↔ Gray, BGR ↔ HSV, etc.
In addition to that, we will create an application to extract a colored object in a video.

### Changing Color-space
There are more than 150 color-space conversion methods available in OpenCV. But we 
will look into only two, which are most widely used ones: BGR ↔ Gray and BGR ↔ HSV.

### Object Tracking
* Take each frame of the video.
* Convert from BGR to HSV color-space.
* Threshold the HSV image for a range of blue color.
* Now extract the blue object alone
