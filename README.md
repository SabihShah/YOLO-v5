# YOLO-v5

This repository contains an implementation of YOLOv5, a state-of-the-art object detection model, in PyTorch. YOLOv5 is a fast, accurate, and easy-to-use object detection model that achieves impressive performance on various datasets.

### Features
- Efficient Architecture: YOLOv5 is built upon the concept of one-stage object detection, making it faster than traditional two-stage detectors while maintaining high accuracy.
- Flexible: YOLOv5 supports various input sizes and can easily adapt to different tasks and datasets.
- Easy-to-Use: With simple configuration files and pre-trained weights, YOLOv5 can be trained and deployed with minimal effort.
- State-of-the-Art Performance: YOLOv5 achieves state-of-the-art performance on standard object detection benchmarks, including COCO.

### Model
The Custom_Object_Detection_using_YOLOv5.ipynb Jupyter Notebook contains all the code and is one-click runnable. The experiments available in the notebook are:
- Training a small YOLOv5 model.
- Training a medium YOLOv5 model.
- Training a medium YOLOv5 model by freezing the first 15 blocks.
Follow the notebook to train your own model on a custom dataset.

```
git clone https://github.com/ultralytics/yolov5
```
```
pip install -r requirements.txt
```

``` Note: If 'Custom_object_detection_using_yolov5' notebook does not open, refer to https://learnopencv.com/custom-object-detection-training-using-yolov5/ ```

### Acknowledgements
- YOLOv5 is developed by Ultralytics LLC. Visit the official repository for more information.
- This implementation is based on the original YOLOv5 codebase.
