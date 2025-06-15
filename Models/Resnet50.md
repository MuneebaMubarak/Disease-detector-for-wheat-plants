#  ResNet50 Model

##  Why ResNet50?
- Handles deep networks using residual learning
- Reduces vanishing gradient problem
- Ideal for multiclass classification

##  Use in This Project
- Used for:
  - Healthy vs Diseased
  - Rust vs Smut
  - Severity Scoring (Low, Medium, High)

##  Results
- Achieved 96% accuracy on scoring test
- Performed well even with image variation

##  Technical Details
- Pretrained on ImageNet
- Fine-tuned with wheat dataset
- Optimized with learning rate scheduler
