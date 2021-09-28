# Image_Alignment_correction
It picks the scanned images that are not perfectly aligned with the horizontal and vertical axes, and align it correctly with respect to the horizontal and vertical axes.
I have used OpenCV minAreaRect method for calculating the angle at which the image is currently aligned to the base and using that angle, I have created a Rotation Matrix through which i have performed the wrap operation over the original image to align it horizontally and vertically.
