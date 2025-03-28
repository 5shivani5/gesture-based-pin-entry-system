# gesture-based-pin-entry-system
Overview
This project implements a gesture-based PIN entry system where users select numbers by pointing at them on a virtual keyboard. The system detects hand gestures using MediaPipe and classifies them using a Convolutional Neural Network (CNN) model.

Features
Virtual keyboard appears on the screen

Users select digits by pointing at them

Hand tracking powered by MediaPipe

Gesture classification using a CNN model

Secure and contactless PIN entry

Tech Stack
Python (Primary language)

MediaPipe (Hand tracking)

TensorFlow/Keras (For CNN model)

OpenCV (For real-time video processing)

System Flow
Hand Detection: MediaPipe detects and tracks the user’s hand.

Gesture Recognition: The CNN model classifies the pointing gesture.

Virtual Keyboard Interaction: The detected gesture selects a number on the screen.

PIN Entry Confirmation: The user completes the PIN entry process.

Dataset
300+ images collected per digit

Gesture data preprocessed before training

Model trained using Categorical Crossentropy loss and Adam optimizer
