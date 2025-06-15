
The proposed project aims to address the pressing issue of limited access to agricultural knowledge in rural Pakistan, specifically targeting wheat farmers facing the challenges of Rust and Smut diseases and to provide an accessible AI solution using Deep Learning models. This project helps early diagnosis for the diseased plants by providinng an easy accessible web interface that leads to minimize  yield loss.

##  Project Highlights
-  Disease Coverage: Rust (Brown, Stem, Stripe) & Smut (Loose, Flag)
-  Dataset: 10,000 images from 6 field visits in Sindh, Pakistan
-  Models Used: YOLOv8, InceptionResNetV2, ResNet50
-  Interface: Built using Django + React
-  Impact: Supports food security, boosts farmer confidence

## Folder Structure
Data Folder → Sample wheat images (Healthy, Rust, Smut)
Models Folder → YOLOv8, ResNet50, InceptionResNetV2 docs
Interface Folder → Screenshots of the web app
Results Folder → Model results and graphs
Notebooks Folder → Training notebooks

##  Models Used
- YOLOv8 (Finalized)
- InceptionResNetV2
- ResNet50

##  Tools & Tech
- Python, TensorFlow, PyTorch, OprnCV
- Google Colab, Jupyter Notebook
- Django + ReactJS for frontend & backend

##  Results
YOLOv8 provided fast real-time detection with almost 98% accuracy.

There were 10% of each model’s dataset randomly selected from the whole dataset which the model never saw it neither in training nor in validation process. These images were used to test each model, besides that other datasets from Kaggle were used to test the model. These three models which were the main models (healthy vs diseased, rust vs smut and brown rust vs stem rust) showed high accuracy nearing perfection when tested using the subset of the dataset which the team collected.

1) Healthy vs Diseased Confusion matrix with 10% of collected data
![Healthy_vs_Diseased_Confusion_matrix](https://github.com/user-attachments/assets/a655d5bc-7474-4b69-aecb-ed50112e23f1)

2) Brown Rust vs Stem rust Confusion matrix
![BrownRust_vs_StemRust_conf_matrix](https://github.com/user-attachments/assets/29300a2b-0357-4d01-bc30-185ce722083c)

3) Rust vs Smut Confusion matrix
![Rust_vs_Smut_confusion_matrix](https://github.com/user-attachments/assets/1b6f16e1-cbb2-419a-b863-5ff290bfa1b7)



## Data Collection
The project's main objective is to collect a valuable dataset of 1000 images containing healthy, Stem Rust, Stripe Rust and Smut to train a reliable machine-learning model that can correctly recognize and categorize plant diseases from photos. This will enable farmers to protect their crops and boost productivity by acting quickly.

## Collected Healthy wheat
![Healthy_14](https://github.com/user-attachments/assets/d27f65ec-951e-4877-85c0-0ae1350e4116)


## Collected Smut
![Loose_Smut_2](https://github.com/user-attachments/assets/2bf88c35-7106-49d3-b7e0-c6b4cf0a753d)


## Collected Rust
![Brown_Rust_3](https://github.com/user-attachments/assets/864174b9-ec81-43f1-adae-c1a97767c7df)






