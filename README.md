# ICDEC-2024-Challenge-Vehicle-Detection-in-Various-Weather-Conditions-VDVWC
# Vehicle Detection Project

This challenge focuses on developing a robust vehicle detection system using the RT-DETR (Real-Time Detection Transformer) model. The system is designed to accurately identify various types of vehicles under different weather and lighting conditions, including rainy, sunny, day, and night scenarios.

## Model and Method

The RT-DETR model is a Transformer-based object detection model pre-trained on the COCO dataset, ensuring high accuracy and real-time performance. For this challenge, the large version of the model (RT-DETR-l) was fine-tuned on our custom vehicle detection dataset.

## Dataset Description

- **Training Set**: 2600 images and their corresponding labels.
- **Validation Set**: 200 images and their corresponding labels.
- **Label Format**: YOLO format, which includes the class ID and bounding box coordinates normalized to the image dimensions.
- **Classes**:
  - car
  - bike
  - auto
  - rickshaw
  - cycle
  - bus
  - minitruck
  - truck
  - van
  - taxi
  - motorvan
  - toto
  - train
  - boat
  - cycle van

The dataset comprises vehicle images captured under various scenarios, including:
- Rainy conditions
- Sunny conditions
- Daytime
- Nighttime

## Training Configuration

The training process involved the following configuration:
- **Epochs**: 53
- **Image Size**: 640 pixels

## Model Link
https://drive.google.com/drive/folders/1UiYrzcx-sSp0wI4YRELTCfxEHtCHFh-Z?usp=sharing

## Conclusion

This challenge successfully demonstrated the effectiveness of the RT-DETR model in vehicle detection across varying weather and lighting scenarios. The use of Transformer-based architecture contributed to the model's robustness and real-time performance, making it suitable for real-world applications in dynamic environments.
