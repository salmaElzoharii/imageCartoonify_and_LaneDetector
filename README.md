# imageCartoonify_and_LaneDetector
Part 1 -Cartoonify images:

In this part,we cartoonified images by applying image processing techniques as median filter to remove noise before applying  Laplacian filter to detect edges then applying a threshold on the output.
Second step was applying a bilateral filter on the original image to smooth the image while preserving the edges.
Final step is applying the edge mask obtained from thresholding on the painting sketch obtained from the bilateral filter .

Part 2 -Road Lane Detection Using Hough Transform:

This part explains a pipeline for detecting lane lines on a road , focusing on edge detection, defining a region of interest (ROI), and using the Hough Transform to detect lines.
