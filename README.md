
# **Car Parking Space Counter**

This project is an intelligent Car Parking Space Counter developed using Python and OpenCV. It automatically detects and counts the number of occupied and free parking slots from a live video feed or static aerial image of a parking lot.

## Features

* Real-time Parking Space Detection using contour detection and pixel intensity analysis.

* Slot Status Visualization: Each parking slot is outlined in:
🟥 Red (occupied)
🟩 Green (free)
* Dynamic Counter Display: The total number of free and occupied spots is displayed clearly on the output image/video.
* Optimized for Overhead Views: Ideal for surveillance drone footage or top-down CCTV angles.
* Custom Slot Mapping: Parking spot positions are pre-defined using manual or semi-automated detection.

## Installation

To install the libraries used in this project, follow the steps below:

```bash
  pip install openCV
  pip install cvzone
  pip install numpy
  pip install pickle
```
    
![Logo](https://github.com/onoriode2024/Car-Parking-Space-Counter/blob/main/overview.png?raw=true)


## Running OpenCV Tests

To run the OpenCV tests, run the following command

```bash
  python main.py
```

## Running Heroku Tests

To run Heroku deployment tests, run the following link


```bash
  python main.py
```

## Deployment

Steps To Deploy This Project

prepare your dataset:

  1. Image Extraction
  2. Building OpenCV API
  3. Pushing code to Github
  4. Connecting to your Heroku account
  5. Deploy Project

