# rc-info-extractor
Developed a text detection model for reading RCs using Tesseract optical character recognition engine in python, and used Image enhancement functions for preprocessing the RC images.

APIs like AWS textract, Google vision etc can be use to give us better results, but for learning purpose i have not implement it in that way.

We should be able to capture the following fields on the RC: 
- License plate number or Regn number
- VIN number or Chassis number (typically 17 digit long)
- Name
- Engine number
- Registration date
- Mfg. date

image preprocessing steps -

edge detection for perspective transform -

![Alt text](edge%20detection.JPG?raw=true "edge detection")


perspective transform - 

![Alt text](/perspective%20transform.JPG?raw=true "perspective transform")


AT last some Image enhancement techniques such as grayscale, contrast etc
