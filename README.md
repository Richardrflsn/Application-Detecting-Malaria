# Application Detecting Malaria
Using Image Analysis and Machine Learning

This repository contains a GUI-based application for detecting malaria from cell images using a custom Convolutional Neural Network (CNN) model with an accuracy of 95.22%. The application is built with Python and uses the Tkinter module for the user interface. The deep learning model was trained and tested in Google Colab using a dataset obtained from Kaggle.

# Dataset

The dataset used for training the model can be found on Kaggle: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

# Features

1. Upload cell images in JPEG, PNG, or JPG format.
2. Scans and augments the uploaded image.
3. Uses a custom-trained CNN model to predict if the cell image is parasitized or uninfected.
4. Displays the prediction result in a user-friendly manner.

# Installations

1. Clone the repository:
```bash
  git clone https://github.com/yourusername/Malaria-Detection-Application.git
cd Malaria-Detection-Application
```

2. Install the required dependencies
   
3. Ensure you have the trained model file saved as model.h5 in the root directory of the project.
   
4. Run the application:
```bash
  python application.py
```

# Application Workflow

1. Upload Image: The user can upload the medical test image through a workstation running on Windows OS. The image should be in JPEG, PNG, or JPG format.

2. Read Image: The image will be scanned before augmentation takes place.

3. Transform Image: The scanned image is then transformed into a format that is needed by the saved custom model.

4. Evaluate Image using Saved Model: The saved custom model creates a feature map of the uploaded medical test image and predicts the output.

5. Determine and Analyze the Output: The predicted output is then analyzed and converted to a user-friendly language.

6. Display the Output: The analyzed result is then displayed to the user.

# Acknowledgments

- Kaggle for providing the dataset.
- The open-source community for their invaluable contributions to the libraries and frameworks used in this project.
