Face Mask Detection System
                                                                                                                                                                                                                                                                                
Description
This repository contains a Convolutional Neural Network (CNN)-based face mask detection system. It classifies images into two categories: "With Mask" and "Without Mask." The project includes data preprocessing, model architecture definition, training, and performance evaluation.

The model is built using TensorFlow, OpenCV, and Python.

Dataset
The dataset is not included in this repository. You need to download the dataset from Kaggle. Ensure the dataset is structured as follows:
data/
├── with_mask/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── without_mask/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
Steps to Download the Dataset:
Visit Kaggle's Face Mask Detection Dataset (search for appropriate datasets).
Download and extract the dataset.
Place the extracted folders inside a directory named data/ in the project root.
How to Use
Clone the repository:
git clone https://github.com/username/Face-Mask-Detection-System.git
cd Face-Mask-Detection-System
Install dependencies:
pip install -r requirements.txt
Place the dataset as per the directory structure mentioned above.

Run the project:
python main.py
Features
Preprocesses images for consistency.
CNN-based architecture for high accuracy.
Evaluates performance using validation data.
Future Enhancements
Add real-time video detection.
Deploy the model as a web or mobile application.
