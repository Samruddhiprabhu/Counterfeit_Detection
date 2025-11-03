#  Counterfeit Brand Detection System
A deep learning project utilizing a Convolutional Neural Network (CNN) built with TensorFlow and a simple, interactive web interface powered by Gradio for classifying products as either Fake or Genuine.

# Features

* Binary Image Classification: Classifies input images into two categories: "Fake" or "Genuine."
* Custom CNN Architecture: Uses a Sequential model with multiple Convolutional and Pooling layers for robust feature extraction.
* Data Preprocessing: Implements image resizing (128x128) and normalization (1/255) using Keras's ImageDataGenerator.
* Live Demo Interface: Deploys the trained model via a **Gradio** interface for immediate, visual testing.

# Technologies & Libraries

* Deep Learning: TensorFlow
* Computer Vision: OpenCV (cv2)
* Data Handling: NumPy, Pillow (PIL)
* Web Interface: Gradio
