This project focuses on recognizing sign language gestures using computer vision and machine learning. The system is trained to identify specific hand signs commonly used in basic conversations. Our model can recognize the following signs:

BYE
HELLO
NO
PERFECT
THANK YOU
YES
This project is aimed at enhancing communication accessibility for the deaf and hard-of-hearing communities.

Dataset
The dataset used for training and testing includes images and videos representing each of the above gestures. Each sign is performed by multiple participants to account for variations in individual style and angle.

Features
Real-Time Detection: Capable of recognizing gestures in real-time via webcam.
Model Training: Customizable model architecture for further training or fine-tuning.
Accuracy Metrics: Performance metrics are provided to evaluate recognition accuracy.

Technologies Used
Python
OpenCV
TensorFlow/Keras (for deep learning model training)

Installation
Clone this repository:
git clone https://github.com/Rohit09sep/Sign-language-recognition
Install dependencies:
pip install -r requirements.txt

Usage
Run the script to start real-time sign language recognition:
python recognize_sign_language.py
Use the webcam to display any of the six signs and see the recognition output on-screen.

Model Training
To train the model with your dataset:

Place your images/videos in the specified folder structure under data/.
Run the training script:
python train_model.py

Contribution
Feel free to contribute by reporting issues or submitting pull requests.
