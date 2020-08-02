# ComputerVisionAlgorithms
I made 3 Interactive Projects using Python+ OpenCV  

Project # 1: Building a Motion Detector App 

Using Background Detection techniques: Foreground detection is one of the major tasks in the field of computer vision and image processing whose aim is to detect changes in image sequences. Background subtraction is any technique which allows an image's foreground to be extracted for further processing (object recognition etc.).
Understand more about it: https://en.wikipedia.org/wiki/Foreground_detection

Here we are making an assumption that the first frame is a frame with no motion and based on that first frame motion will be detected.

Motion Analysis:
1. resize image down
2. create black and white image and Gaussian Image (to detect tiny intensity values across a defined average)
3. save the first frame. We suppose the first frame creates no motion (the first frame should be the static background)
4. Simple Thresholding: Here, the matter is straight forward. If pixel value is greater than a threshold value, it is assigned one value (may be white), else it is assigned another value (may be black). 
5. Dilation
6. compare current frame with saved first frame.

Project # 2: Building a Hand Detector App 
Project #3 : Face Recognition App


Documentation for this project:
link will be soon published
