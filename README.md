 # License Plate Recognition Using YOLOv5
 
This repository contains a tailor-made model for License Plate Recognition built using YOLOv5s. It aims to identify license plates from various vehicles and draws a bounding box around the detected license plate. Additionally, it uses the `EasyOCR` library to extract the registration number from the detected plates. The model works efficiently on photos, videos and also real-time footage from cameras.


## Installation Requirements 

- Python 3
- YOLOv5
- PyTorch 
- OpenCV-Python
- EasyOCR


## Results 

Our model achieves the following results:
- mAP50: 0.906
- mAP50-95: 0.513


This significant accuracy is achieved by training the model using annotated images: photographs of license plates with corresponding coordinates for bounding boxes.
