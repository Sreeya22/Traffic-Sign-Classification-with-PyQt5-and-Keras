
# Traffic Sign Classification with PyQt5 and Keras



This project develops a traffic sign recognition application using PyQt5 for the graphical user interface and Keras for the machine learning model. The application allows users to browse and classify traffic sign images, leveraging a trained Convolutional Neural Network (CNN) to recognize 43 different traffic signs.



## Features

- User-friendly GUI for loading and classifying traffic sign images.
- Trained CNN model capable of recognizing 43 traffic sign classes.
- Visualization of training results, including accuracy and loss plots.
- Ability to save the trained model for future use.



## Dataset

The model is trained on a dataset containing images of 43 different traffic signs. Ensure the dataset is organized as follows:

- **Training Images**: `/dataset/train`
- **Testing Images**: `/dataset/test`

Please update the paths in the code to point to your dataset.


## Model Architecture

The CNN model consists of:
- Multiple convolutional layers for feature extraction.
- Max pooling layers for dimensionality reduction.
- Dropout layers for regularization.
- Dense layers for final classification.

## Results

Training metrics are visualized through plots generated during training. Model is saved.

