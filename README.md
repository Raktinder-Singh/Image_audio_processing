# Image_audio_processing
This project is related to Image processing and Audio Processing. In image processing i had made two folders one for dataset images and the second one for output images. After that there comes the code file in which the source for image processing is written.
*#Image Processing*
Step 1: The first step is about preprocess all the images inside the dataset images. I first define all the libraries and the input and output folders path. Then the target width and quality of the images are defined. Then i used for loop for iteration and all the processed images will be stored in the folder named output folder.

Step 2: The next step involves the noise reduction. In this by using gaussion blur function I performed noise reduction on input images and plot the output.

Step 3: This step includes the calculation of sobel operator in terms of x and y axis. Then the process of displaying the output is same.

Step 4: Then comes the Non maximum Supression which is used to eliminate duplicate detections. It select the most relevant bounding boxes that correspond to the detected objects. Then the threshold values are defined for edge detection and the last step includes the hysteresis to detect edges.


**Audio Processing**
I set the folder anf file paths for the audio files. Then I load the audios in variables for easy access. After that i loaded the files and play some sample audio files. Then i check the magnitude frequency of the audio files named Morning1, Morning2 and evening1. The last step is to check the mean difference of the audio files.
