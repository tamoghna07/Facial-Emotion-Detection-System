# Dataset link -> https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer
# Facial Emotion Detection System using Convolutional Neural Networks (CNN)

## Overview

This project aims to detect facial emotions using a Convolutional Neural Network (CNN). The system is capable of recognizing seven primary emotions: 'Angry', 'Disgust', 'Fear', 'Happy', 'Neutral', 'Sad', and 'Surprise'. It processes real-time video or image data from a camera feed, extracts facial features, and predicts the predominant emotion being expressed by the individual in the frame.

## Folder Structure

- `app.py`: Contains the main application code for real-time emotion detection.
- `emo.ipynb`: Jupyter Notebook file containing code for training the CNN model and exploring data.
- `main.py`: Alternative main script for running the application.

## Installation

### Requirements
- Python (>=3.6)
- TensorFlow (>=2.0)
- OpenCV (>=4.0)
- NumPy

### Installation Steps

1. Clone the repository:
git clone https://github.com/royswastik07/facial_emotion_detection.git

2. Install the required dependencies:
pip install -r requirements.txt


3. Run the main script:
python main.py


This will start the camera feed and display real-time emotion predictions on the screen.

### Additional Options

- `--image` flag: Allows you to provide an image file instead of accessing the camera feed. Example usage:


## Model Training

The CNN model used for emotion detection was trained on a dataset containing labeled facial expressions. The training script, along with the dataset used, can be found in the `emo.ipynb` Jupyter Notebook file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of the facial emotion datasets and the TensorFlow and OpenCV communities for their valuable contributions to the field of computer vision.

