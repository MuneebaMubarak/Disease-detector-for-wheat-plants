#  YOLOv8 Model

##  Why YOLOv8?
- Suitable for real-time object detection
- Efficient on mobile and embedded systems
- Speed and accuracy of model yolov8 is very high for pre-trained weights and fine-tuned parameters
- well suitable for working with custom dataset which makes it ideal for our project where we collected around 10,000 images and annotated them accordingly
- It is possible to handle images of any size with newer YOLO architectures without the need for an adaptive pooling layer. 

##  Use in This Project
- Used to detect Healthy vs Diseased
- Used to detect Rust vs Smut
- Trained on field-captured data
- Achieved fast detection with ~89% accuracy

##  Output
- Bounding boxes for disease on wheat leaves
- Our wheat dataset has nearly 10,000 images for four classes such as healthy, brown rust, stem rust and loose smut. We trained our yolov8 model for this dataset in 100 epochs

##  Technical Details
- Based on Ultralytics implementation
- Loss function
- Trained on Google Colab with GPU
