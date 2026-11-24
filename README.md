🛣️ Pothole Detection Using YOLO11
Custom Object Detection Model | Google Colab

This repository contains the complete implementation of a Pothole Detection System using YOLO11. The project demonstrates the entire object detection pipeline, starting from dataset downloading and preparation to model training, evaluation, and visualization of prediction results.

✨ Features
📥 Automatic Dataset Download: Download the dataset directly using gdown.
📂 Dataset Organization: Automatically arrange files into the required YOLO directory structure.
⚙️ YAML Configuration: Generate the pothole.yaml configuration file programmatically.
🧠 Model Training: Train YOLO11 using customized training parameters.
⏹️ Early Stopping: Prevent unnecessary training and save the best-performing model checkpoint.
🎯 Detection Visualization: Display prediction results using customized bounding boxes.
🖼️ Result Visualization: Display 16 randomly selected test images in a 4×4 grid.
📁 Dataset

The pothole detection dataset is available on Google Drive.

Dataset Link: https://drive.google.com/drive/folders/1NWhSWYf19Mf9FQnNfNpyYgIEjuLBZhDV?usp=drive_link

The dataset is downloaded automatically using gdown and organized into the required YOLO directory structure through the notebook.

🛠️ Technologies Used
Python
YOLO11
Google Colab
OpenCV
gdown
Ultralytics
🚀 Project Workflow
Download the pothole detection dataset.
Organize the dataset into the YOLO directory structure.
Generate the dataset configuration file.
Configure and train the YOLO11 model.
Apply early stopping and save the best model weights.
Test the trained model on sample images.
Visualize detection results using bounding boxes.
Display 16 random predictions in a 4×4 grid.
📊 Results

The notebook includes visualizations of pothole detection predictions on test images, making it easier to evaluate the model's performance and detection capabilities.

💻 Getting Started

Open the notebook in Google Colab and run the cells sequentially to download the dataset, train the YOLO11 model, and visualize the detection results.

⭐ If you find this project useful, consider giving this repository a star!
