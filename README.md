# ShapeDetection
#
This is a simple python project exploring the usage of OpenCV library to identify different shapes from a given image.
It uses the findContours function from cv2 library to get contours.
The contours is then used to craet a perimeter with arcLength and then we approximate our polygonal Curves.
The length of approximation is then used to detemine the shapes of the objects.
