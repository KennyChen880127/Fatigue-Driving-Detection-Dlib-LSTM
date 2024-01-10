# Fatigue-Driving-Detection-Dlib-LSTM
This project utilizes the machine learning library Dlib to capture facial landmarks, particularly focusing on eye features. Subsequently, the data is processed through the machine learning frameworks Tensorflow and Keras to construct a Long Short-Term Memory (LSTM) network. The LSTM is trained on Eye Aspect Ratio (EAR) data, enabling it to learn patterns and make predictions. The ultimate goal is to implement a system for detecting driver fatigue.

## Dlib
[Dlib](http://dlib.net/) is a comprehensive library encompassing machine learning, computer vision, image processing, and more. Developed in C++, it is widely adopted in both industrial and academic settings. Its applications span across robotics, embedded systems, mobile devices, and large-scale computing architectures. Notably, dlib is open-source, free of charge, and platform-agnostic, supporting Linux, Mac OS, and Windows. Additionally, it offers a Python API in addition to its C++ implementation.

## LSTM
LSTM (Long Short-Term Memory) is a deep learning, sequential neural network that allows information to persist. It is a special type of Recurrent Neural Network which is capable of handling the vanishing gradient problem faced by RNN. LSTM was designed by Hochreiter and Schmidhuber that resolves the problem caused by traditional rnns and machine learning algorithms. LSTM Model can be implemented in Python using the Keras library.

### Results
| Driver is not fatigued. | Driver is fatigued. |
| ------------- | ------------- |
| ![ex1]() | ![ex2]() |
