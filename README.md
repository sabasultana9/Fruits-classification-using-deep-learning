Fruit Classification Using Tiny YOLO and Neural Networks

This project demonstrates the classification of fruits using deep learning techniques, specifically utilizing Tiny YOLO (You Only Look Once) and other neural network architectures such as autoencoders and fully connected networks. The goal of this project is to identify and classify various fruits from images.

Table of Contents
	1.	Introduction
	2.	Technologies Used
	3.	Dataset
	4.	Model Architecture
	5.	Installation
	6.	Usage
	7.	Results
	8.	Contributing
	9.	License

Introduction

The Fruit Classification project uses a combination of Tiny YOLO and neural networks to identify fruits in images. The model can classify fruits with a high degree of accuracy, leveraging transfer learning and fine-tuning to improve performance.

Technologies Used
	•	Tiny YOLO: A compact version of the YOLO model, designed for faster and more efficient real-time object detection.
	•	Autoencoders: Used for feature extraction and dimensionality reduction.
	•	Fully Connected Networks: Used in the final classification stage for categorizing fruits based on the extracted features.
	•	Flask: A web framework used to build a simple web application for the fruit classification system.
	•	Python: Programming language for implementing the model.
	•	TensorFlow/Keras: Deep learning libraries used for training the neural networks.

Dataset

This project uses a publicly available dataset of fruit images, which includes images of various fruits like apples, bananas, oranges, etc. The images are pre-processed and augmented to improve the robustness of the model.

Model Architecture
	1.	Tiny YOLO: Used as the primary object detection model for identifying regions of interest (fruits) in an image.
	2.	Autoencoders: Used for reducing the input dimensionality and extracting important features of the fruit images.
	3.	Fully Connected Network: Classifies the extracted features into one of the pre-defined fruit categories.

Installation
	1.	Clone this repository:

git clone https://github.com/sabasultana9/Fruits-classification-using-deep-learning.git
cd fruit-classification


	2.	Install the required dependencies:

pip install -r requirements.txt



Usage
	1.	To run the project locally, use the following command:

python app.py


	2.	Visit http://localhost:5000 on your browser to interact with the classification application.
	3.	Upload an image of a fruit, and the model will classify it and display the result.

Results

The model achieves an accuracy of around XX% on the test set, successfully classifying various fruits with real-time detection. The results are visualized by drawing bounding boxes around the detected fruits and displaying their predicted labels.

Contributing

If you would like to contribute to this project, feel free to fork the repository and submit pull requests. Contributions to improve the classification model or the web interface are welcome!

License

This project is licensed under the MIT License - see the LICENSE file for details.

# Fruits-classification-using-deep-learning
