# Fire-and-smoke-detection-using-Yolo-v8-

Overview
This project aims to create a reliable system for detecting and tracking fires and smoke using the latest YOLOv8 object detection model. Our custom model, Fire-YOLOv8, is designed to identify even the smallest fires and smoke in various settings, achieving impressive accuracy and speed.

Methodology
We use YOLOv8’s advanced architecture to ensure our system is both accurate and fast. Here’s how it works:

Grid Division: The input images are divided into grids to pinpoint the exact location of the fire or smoke.
Bounding Box Prediction: Each grid cell predicts multiple bounding boxes with confidence scores.
Class Prediction: Probabilities for different classes are predicted for each bounding box.
Confidence Thresholding: This step filters out low-confidence predictions to reduce false alarms.
Non-Maximum Suppression: Eliminates duplicate detections to improve accuracy.

Key Advancements
Enhanced Accuracy and Speed: Crucial for real-time detection.
TensorFlow Lite Compatibility: Allows deployment on various platforms, including mobile and embedded systems.
Advanced Data Augmentation: Strategies like MixUp and CutMix improve model robustness and generalization.

Results
Our fine-tuned YOLOv8 model delivers high efficiency and real-time detection capabilities, making it highly effective for detecting fire and smoke in diverse conditions.

Conclusion
The Fire-YOLOv8 model significantly improves fire and smoke detection accuracy, providing robust performance for rapid response and safety monitoring. This makes it a valuable tool for various applications, from residential safety to forest fire management.
