# Custom Object Detection with YOLOv5

This project demonstrates how to perform custom object detection using YOLOv5. It includes two code files:

**Code File 1 (Training):**

This file is responsible for training the YOLOv5 model on a custom dataset. Here are the steps covered in this file:

1. Mounting Google Drive for data storage.
2. Cloning the YOLOv5 repository.
3. Installing the required dependencies.
4. Downloading and formatting the custom dataset using Roboflow.
5. Beginning custom training with specified hyperparameters.
6. Evaluating the trained model's performance on test data.
7. Displaying inference on test images.
8. Optionally, zipping the model weights and results for local download.

**Code File 2 (Inference):**

This file is responsible for performing real-time object detection using a pre-trained YOLOv5 model. Here are the steps covered in this file:

1. Importing necessary libraries.
2. Loading a pre-trained YOLOv5 model.
3. Defining a function for real-time object detection from a webcam feed.
4. Running the real-time object detection function.

## Getting Started

Before running the code, follow these steps:

**Code File 1 (Training):**

1. Ensure you have a GPU runtime selected (Runtime --> Change Runtime Type --> Hardware accelerator --> GPU).
2. Mount your Google Drive to store data and results.
3. Clone the YOLOv5 repository and install the required dependencies.
4. Use Roboflow to download and format your custom dataset.
5. Modify the training parameters (e.g., batch size, number of epochs) as needed.
6. Run the code to begin training. Training progress will be displayed.
7. Evaluate the trained model's performance on test data.
8. Optionally, view inference results on test images or zip the results for local download.

**Code File 2 (Inference):**

1. Import the necessary libraries.
2. Load the pre-trained YOLOv5 model.
3. Define a function for real-time object detection from the webcam feed.
4. Run the real-time object detection function to detect objects in real-time.

## Custom Object Detection

The training code file allows you to train YOLOv5 on your custom dataset. Ensure that your dataset is correctly formatted with YOLO TXT annotations, a custom YAML file, and organized directories.

The inference code file demonstrates real-time object detection using a pre-trained model. It captures video frames from the webcam feed, performs object detection, and displays bounding boxes around detected objects.

Customize the code, hyperparameters, and paths according to your dataset and requirements. For any questions or issues, feel free to reach out.

**Note**: Ensure that you have the necessary dataset and data paths set correctly before running the training code. For real-time object detection, make sure you have a webcam connected and accessible to the runtime environment.
