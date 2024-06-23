# Object-Detection-with-YOLO
YOLO-tiny implementation which uses Mobilenet-v2 as backbone. It is designed for performing real-time object detection on cpu without any need for gpu accelerators.

## Dataset
@misc{ vehicle-detection-fhsfn_dataset, title = { vehicle detection Dataset }, type = { Open Source Dataset }, author = { vehicle }, howpublished = { \url{ https://universe.roboflow.com/vehicle-adiop/vehicle-detection-fhsfn } }, url = { https://universe.roboflow.com/vehicle-adiop/vehicle-detection-fhsfn }, journal = { Roboflow Universe }, publisher = { Roboflow }, year = { 2024 }, month = { jun }, note = { visited on 2024-06-15 }, }

I performed some preprocessing operations and applied augmentation techniques using roboflow before using the dataset.

Preprocessing
    Auto-Orient: Applied
    Resize: Stretch to 700x700

Augmentations
    Crop: 0% Minimum Zoom, 25% Maximum Zoom
    Shear: ±15° Horizontal, ±15° Vertical