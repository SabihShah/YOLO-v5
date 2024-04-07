# YOLO-v5

This repository contains an implementation of YOLOv5, a state-of-the-art object detection model, in PyTorch. YOLOv5 is a fast, accurate, and easy-to-use object detection model that achieves impressive performance on various datasets.

### Features
- Efficient Architecture: YOLOv5 is built upon the concept of one-stage object detection, making it faster than traditional two-stage detectors while maintaining high accuracy.
- Flexible: YOLOv5 supports various input sizes and can easily adapt to different tasks and datasets.
- Easy-to-Use: With simple configuration files and pre-trained weights, YOLOv5 can be trained and deployed with minimal effort.
- State-of-the-Art Performance: YOLOv5 achieves state-of-the-art performance on standard object detection benchmarks, including COCO.

### Model
- The model is trained on a subset of the PascalVoc2012 dataset.
- Follow the notebook to train your own model on a custom dataset.
- In the notebook the directory 'working' is created inside the yolov5 directory.

```
git clone https://github.com/ultralytics/yolov5
```
```
pip install -qr requirements.txt
```

### Acknowledgements
- YOLOv5 is developed by Ultralytics LLC. Visit the official repository for more information.
- This implementation is based on the original YOLOv5 codebase.
