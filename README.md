# LaneLines
A pipeline based on OpenCV for recognizing lane lines in video streams.

The code may be found in the P1.ipynb file.

To begin, I use the Canny edge detection technique to find edges. The photos are then represented in parameter space using the Hough transform, which allows me to detect lines in the region of interest. This is tried on photos first, then on videos.
