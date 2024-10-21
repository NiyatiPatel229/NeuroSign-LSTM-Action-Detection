# NeuroSign-LSTM-Action-Detection

NeuroSign-LSTM-Action-Detection is a real-time action detection system focused on interpreting sign language gestures using LSTM (Long Short-Term Memory) deep learning models. This project aims to help bridge the communication gap between individuals with hearing or speech impairments and the general public by recognizing common sign language actions through computer vision techniques.<br/>
## Features 
* Real-Time Action Detection : Detects and recognizes sign language gestures such as "hello", "thanks", and "I love you" in real time using a webcam feed. 
* LSTM Architecture: Utilizes LSTM to capture temporal dependencies in motion-based gestures for accurate prediction.
* MediaPipe Integration : Leverages Google’s MediaPipe for hand landmark detection and tracking, ensuring precise gesture recognition.
* Efficient Preprocessing: Processes webcam input in real time, applying necessary preprocessing steps to detect hand gestures.
* User-Friendly Interface : A clean and intuitive interface, making it easy for users to interact and test various sign language gestures.
## Technologies and Tools Used
* Python: Core programming language.
* TensorFlow/Keras: For building and training the LSTM-based neural network.
* MediaPipe: For real-time hand tracking and landmark detection.
* OpenCV: For video capture and frame preprocessing.
* NumPy & Pandas: For data handling and preprocessing.
* Matplotlib: For visualizing training results.
## How It Works

* Capture Input: The system captures live video input using a webcam.
* Landmark Detection: MediaPipe detects and tracks hand landmarks from the video frames.
* Preprocessing: The detected landmarks are preprocessed into a format suitable for LSTM.
* Action Prediction: The preprocessed data is passed through the trained LSTM model, which predicts the gesture.
* Output: The recognized gesture is displayed on the screen in real-time.
