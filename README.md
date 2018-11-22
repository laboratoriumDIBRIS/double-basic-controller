# Basic controller for the Double robot

Send low-level commands to the Double robot, access the iPad/iPhone camera and and utter sentences.

This code is intended as the basis for Social Robotics assignments to be done by students enrolled in the European Master in Advanced Robotics (EMARO+) and Robotics Engineering master programmes at the University of Genoa, Italy.

This code has been developed with Xcode 10 under macOS 10.14.1 (Mojave), targeting iOS 12.01.
This code has been tested with an iPad Air 2 running iOS 12.01 and connected to a Double 1 robot.

## Installation

Clone the repository:

    git clone https://github.com/laboratoriumDIBRIS/double-basic-controller.git

## Dependencies

This code relies on:
* OpenCV
* Double Basic Control SDK

### OpenCV

1. [Install OpenCV](https://docs.opencv.org/2.4/doc/tutorials/introduction/ios_install/ios_install.html#ios-installation)
2. Copy <strong>opencv2.framework</strong> in the main folder (where this README is located)

### Double Basic Control SDK

1. Clone (outside of the main folder) the repository:

       git clone https://github.com/doublerobotics/Basic-Control-SDK-iOS.git

2. Copy <strong>DoubleControlSDK.framework</strong> in the main folder (where this README is located)

## Usage

This is an [Xcode](https://developer.apple.com/xcode/) project.

To open it in Xcode, double click on the file <strong>labDouble.xcodeproj</strong> .

## Documentation

[laboratoriumDIBRIS.github.io/double-basic-controller/](https://laboratoriumDIBRIS.github.io/double-basic-controller/)

## Author

[Barbara Bruno](https://github.com/bbbruno) e-mail:barbara.bruno@unige.it

This code relies on the [Double Basic Control SDK](https://github.com/doublerobotics/Basic-Control-SDK-iOS) provided by [Double Robotics](http://www.doublerobotics.com).
