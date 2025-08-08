# Forest-fire-detection-through-ML
This project focuses on detecting forest fires using deep learning models. The system utilizes convolutional neural networks (CNNs) to analyze images and predict the presence of fire. Early detection can help mitigate the damage caused by wildfires and protect natural ecosystems.

Features Automatic fire detection from images

Uses deep learning (CNN-based model)

Trained on a dataset of fire and non-fire images from Kaggle

Supports GPU acceleration for faster training

Real-time monitoring capability (optional integration with live video feeds)

Dataset The dataset is downloaded from Kaggle and consists of images categorized into two classes:

Fire: Images containing visible flames or smoke indicating fire presence.

No Fire: Images without fire-related visual cues.

Technologies Used Python

TensorFlow/Keras

NumPy & Pandas

Matplotlib for visualization

Installation Clone this repository:

git clone https://github.com/yourusername/forest-fire-detection.git cd forest-fire-detection Create and activate a virtual environment:

python -m venv venv source venv/bin/activate # For Linux/macOS venv\Scripts\activate # For Windows Install dependencies:

pip install -r requirements.txt Downloading Dataset Ensure you have access to Kaggle datasets. Download the wildfire dataset:

import kagglehub path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset") print("Path to dataset files:", path) Results Model accuracy and loss graphs are generated after training.

Predictions include confidence scores for fire detection.
