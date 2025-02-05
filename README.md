# SIGHTSVision

This repository contains vision and camera related software created by the Semi-Autonomous Rescue Team for the SART Integrated GUI and Host Teleoperation Service (SIGHTS) project.

![image](https://raw.githubusercontent.com/SFXRescue/SIGHTSVision/master/hazmat/example.png)

## Requirements

### 1. Python Packages

Packages required are Imutils, Scipy, OpenCV, Numpy and Pyzbar. Install with this command:  
```
python -m pip install -r requirements.txt
```

### 2. ZED SDK
The spatial mapping script uses the ZED SDK to interface with ZED, a depth-sensing camera from StereoLabs.

### 3. YOLO Object Detection
This project uses a YOLO object detector to find the signs in an image. The software comes with a weights and cfg file, trained using darknet, which will be interpreted by OpenCV.

## Downloading and Running

The main file for hazmat detection is hazmat_yolo.py. Use the -h flag to see all the available command line settings.
```
python hazmat_yolo.py -h
```

## Contributing

If you have an idea, suggestion or bug report for **SIGHTSVision**, or want to make a contribution of your own, we'd love to work with you to make it happen! Take a look at our [contributing page](https://github.com/SFXRescue/.github/blob/master/CONTRIBUTING.md) for more information.
