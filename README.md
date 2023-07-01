# Number Plate Detection and Saving

This Python script detects number plates in real-time video using OpenCV and saves the detected plates as images.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

```bash
Python 3
OpenCV
haarcascade_russian_plate_number.xml (Haar cascade classifier for number plate detection)
```

## Getting Started

Clone the repository or download the script and 
haarcascade_russian_plate_number.xml file.

```bash
git clone https://github.com/Mohshaikh23/Number_Plate_Recognizer.git
```

Install the required dependencies using pip:

```bash
pip install opencv-python
```

## Usage

Connect a camera or webcam to your system.
Run the script:

```bash
python number_plate_detection.py
```

Example Showcase - 

[Testimonial](https://github.com/Mohshaikh23/Number_Plate_Recognizer/blob/main/Input%20Images/sampled1.png?raw=true)

The script will open a window displaying the video feed from the camera.
If a number plate is detected, it will be outlined with a rectangle, and the text "Number Plate" will be displayed above it.
To save the detected number plate, press the 's' key on your keyboard. The script will capture the plate image, save it with a timestamp in the "Result" directory, and display a confirmation message.
To exit the script, press the 'q' key.
Configuration
You can adjust the following parameters in the script according to your requirements:

frameWidth and frameHeight: Set the width and height of the video frame.
minArea: Set the minimum area required for a detected region to be considered as a number plate.
color: Set the color for drawing rectangles and text (in BGR format).
cap.set(3, frameWidth): Set the camera's frame width.
cap.set(4, frameHeight): Set the camera's frame height.
cap.set(10, 150): Adjust the camera's brightness.
Saving Images
The script saves the detected number plate images in the "Result" directory. Each saved image is named in the format "NoPlate_YYYYMMDD_HHMMSS.jpg", where "YYYYMMDD" represents the date and "HHMMSS" represents the time when the image was saved.

License
This project is licensed under the MIT License.

Feel free to modify and adapt the code according to your needs.

Note: This script is provided as a starting point for number plate detection and saving. Depending on your specific requirements, you may need to customize and enhance the code further.

Please ensure compliance with the legal regulations and privacy considerations in your jurisdiction when using this script for number plate detection.

For any further assistance or inquiries, feel free to contact the author.

Author: Mohsin Shaikh