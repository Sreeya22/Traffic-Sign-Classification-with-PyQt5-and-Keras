
# Traffic Sign Classification with PyQt5 and Keras



This project develops a traffic sign recognition application using PyQt5 for the graphical user interface and Keras for the machine learning model. The application allows users to browse and classify traffic sign images, leveraging a trained Convolutional Neural Network (CNN) to recognize 43 different traffic signs.



## Features

- User-friendly GUI for loading and classifying traffic sign images.
- Trained CNN model capable of recognizing 43 traffic sign classes.
- Visualization of training results, including accuracy and loss plots.
- Ability to save the trained model for future use.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/traffic-sign-classification.git
   ```

2. Navigate to the project directory:
   ```bash
   cd traffic-sign-classification
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The model is trained on a dataset containing images of 43 different traffic signs. Ensure the dataset is organized as follows:

- **Training Images**: `/dataset/train`
- **Testing Images**: `/dataset/test`

Please update the paths in the code to point to your dataset.

## Usage

1. To train the model, run:
   ```bash
   python train_model.py
   ```

2. To launch the GUI application, execute:
   ```bash
   python app.py
   ```

3. In the GUI, browse for traffic sign images to classify and view the results.

## Model Architecture

The CNN model consists of:
- Multiple convolutional layers for feature extraction.
- Max pooling layers for dimensionality reduction.
- Dropout layers for regularization.
- Dense layers for final classification.

## Results

Training metrics are visualized through plots generated during training. Model is saved.

