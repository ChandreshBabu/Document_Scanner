# Document_Scanner
Computer vision project using OpenCV

Here, I have used the computer vision techniques of OpenCV to build this project. The programming language used is Python.

# Algorithm

1.Start reading the frames and convert the captured frames to HSV colour space.  
2.Preprocess the frames with morphological operations.                                                                                                                              3.Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames.                                                      4.Reorder the contours and warp frame using reordered contours.                                                                                                                      5.Finally draw the points stored in array on the frames and canvas.

used some stacking in the last and stacked all the images from all the steps to track the changes and process.
