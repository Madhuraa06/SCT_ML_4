**Hand Gesture Recognition using CNN**
A Deep Learning project that classifies hand gestures (Palm, Fist, OK, etc.) with high accuracy using a Convolutional Neural Network (CNN).

🚀 **Overview**
This project uses TensorFlow and Keras to train a model on the LeapGestRecog dataset. It includes a custom pipeline for image preprocessing, model training, and a real-time inference script that can test single images or generate random batch predictions.

📊 **Key Results**
Training Accuracy: 100% , 
Validation Accuracy: 100% , 
Average Confidence: 99.9% , 
Frameworks: TensorFlow, Keras, OpenCV, Matplotlib.

🛠️ **Project Structure**
hand_gesture_recognition.py: Script to preprocess data and train the CNN model,
combined_prediction.py: Inference script for single-image selection or random batch testing,
hand_gesture_model.h5: The trained weights,
gesture_labels.txt: Mapping of class numbers to gesture names.

⚙️ **How It Works**
Preprocessing: Images are converted to grayscale and resized to pixels to reduce computational load.
CNN Architecture: Features layers for feature extraction (Conv2D), down-sampling (MaxPooling), and a Dense output layer with Softmax activation.
Inference: The model predicts the gesture and provides a confidence score via a bar chart visualization.

💻 **How to Run**
Install dependencies: pip install tensorflow opencv-python matplotlib
Run the predictor: python combined_test.py
