
# Plant Disease Detection using Deep Learning


# Project Overview
This project focuses on the early detection and identification of diseases in crop leaves using advanced deep learning techniques. The primary goal is to assist farmers and agricultural professionals in identifying leaf diseases promptly and accurately, thereby safeguarding crops and ensuring a healthier harvest.

# Dataset Description
The dataset used in this project comprises approximately 87,000 RGB images of both healthy and diseased crop leaves. These images are categorized into 11 distinct classes, each representing a different type of plant condition (healthy or specific diseases). To facilitate effective model training and evaluation, the dataset is divided into an 80/20 ratio for training and validation sets, respectively, while maintaining the directory structure. Additionally, a separate directory containing 16 test images has been created for prediction purposes.

-- Content Breakdown
Batch Size: 32
Training Set: 20,789 images
Validation Set: 5,198 images
Test Set: 16 images

# Mission
Our mission is to provide an efficient and user-friendly tool for identifying leaf diseases. By simply uploading an image of a leaf, users can leverage our system to analyze and detect any signs of diseases. This tool aims to help in the early detection of plant diseases, which is crucial for effective disease management and crop protection.

# How It Works
-- Upload Image: 
Users can navigate to the Disease Recognition page and upload an image of a leaf suspected to have a disease.
-- Analysis: 
The system processes the uploaded image using sophisticated algorithms based on deep learning models trained on the extensive dataset.
-- Results: Users receive the analysis results, which include the identification of any potential diseases and recommendations for further action.

# Get Started
To experience the power of our Plant Disease Detection System, follow these steps:

-- Go to the Disease Recognition page in the sidebar.
Upload an image of a leaf.
View the results and take the necessary actions based on the recommendations provided.

# Project Structure
The project is organized into the following directories:

-- Setup and Installation
-- data/: Contains the dataset.
-- train/: Training set images.
-- validation/: Validation set images.
-- test/: Test images for prediction.
-- notebooks/: Jupyter notebooks for data preprocessing, training, and validation.
-- streamlit_app/: Streamlit web app for disease detection.
-- models/: Saved trained models.


# Prerequisites
Python 3.6 or higher
Required Python libraries: numpy, matplotlib, tensorflow, keras, seaborn, streamlit
