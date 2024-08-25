# Satellite-Image-to-Google-Map-Conversion

#Overview
This project focuses on converting satellite images into Google Map-style representations. The primary objective is to process raw satellite images and produce a more interpretable and user-friendly map view, similar to what is available on Google Maps.

#Methodology
Data Collection:

Satellite images are collected from publicly available datasets or APIs.
Preprocessing:

Images undergo preprocessing, including resizing, normalization, and augmentation, to prepare them for the model.
Preprocessing techniques are used to enhance the quality of images, ensuring better feature extraction.
Model Architecture:

A custom deep learning model is designed for image-to-image translation.
Encoder-decoder architecture is employed, where the encoder compresses the image data and the decoder reconstructs it into the desired map format.
The model includes skip connections to retain high-resolution details, similar to the U-Net architecture.
Training:

The model is trained using a supervised learning approach.
A large dataset of satellite images paired with corresponding map images is used.
Loss functions like Mean Squared Error (MSE) and Structural Similarity Index (SSIM) are used to evaluate the accuracy of the output.
Post-Processing:

The output images are post-processed to improve visual clarity and map readability.
Techniques like contrast adjustment, sharpening, and smoothing are applied.

#Technologies Used
Programming Languages: Python
Libraries/Frameworks: TensorFlow, Keras, OpenCV, NumPy, Matplotlib
Data Sources: Public satellite imagery datasets, Google Maps API
Development Tools: Jupyter Notebook, Google Colab
