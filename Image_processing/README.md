#Image Processing
Step 1: The first step is about preprocess all the images inside the dataset images. I first define all the libraries and the input and output folders path. Then the target width and quality of the images are defined. Then i used for loop for iteration and all the processed images will be stored in the folder named output folder.

Step 2: The next step involves the noise reduction. In this by using gaussion blur function I performed noise reduction on input images and plot the output.

Step 3: This step includes the calculation of sobel operator in terms of x and y axis. Then the process of displaying the output is same.

Step 4: Then comes the Non maximum Supression which is used to eliminate duplicate detections. It select the most relevant bounding boxes that correspond to the detected objects. Then the threshold values are defined for edge detection and the last step includes the hysteresis to detect edges.
