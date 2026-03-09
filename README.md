# AI Object Detection Lab

This project demonstrates **object detection using YOLOv8**.
The script can detect and track objects in **images, videos, and webcam input** using a pretrained YOLOv8 model.

## Project Structure

```
AI-Object-Detection-Lab/
├── README.md
├── lab_1.py
├── Asian market.jpg
├── Cars Moving On Road Footage.mp4
├── screenshots/
│   ├── image-detection-result.png
│   ├── video-tracking-result.png
│   └── cmd-execution.png
└── webcam-demo.mp4
```

### Files Description

* **lab_1.py** – Main Python script used to run YOLOv8 object detection.
* **Asian market.jpg** – Sample image used for testing image detection.
* **Cars Moving On Road Footage.mp4** – Sample video used for testing object tracking.
* **screenshots/** – Contains screenshots showing the results of the program.
* **webcam-demo.mp4** – A recording showing the object detection running on webcam input.

## Requirements

* Python 3.x
* Ultralytics YOLOv8
* OpenCV

Install required packages:

```
pip install ultralytics opencv-python
```

## How to Run

Run the main script:

```
python lab_1.py
```

The script will detect objects in the selected **image, video, or webcam feed** and display the results.

## Example Results

The `screenshots` folder contains examples of:

* Image object detection
* Video object tracking
* Successful command line execution

## Author

Created as part of an **AI Object Detection Lab assignment** using YOLOv8.
