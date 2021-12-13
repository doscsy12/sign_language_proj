# Sign language 
The purpose of this project is to build a sign language classifier that translates a few discrete set of American Sign Language (ASL) signs, using TensorFlow Object-Detection API and OpenCV.


| notebooks              | description                               |
|------------------------|-------------------------------------------|
| collect_data           | Collect data from webcam                  |
| build_model            | Build model                               |

## Setup
To install TensorFlow 2 Object Detection API, refer to the step-by-step guide [here](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#tensorflow-installation). I would suggest you follow the instructions to the word, especially the Environment Setup and the Protobuf Installation. 

Since we would be collecting our own images, make sure that your webcam is working. 

## Model
The model is custom made with three convolutional layers and 3 fully-connected layers. 
![Model architecture](https://github.com/doscsy12/sign_language_proj/blob/main/model.png)

## Conclusion
The main aim of this project was to utilise the Object-Detection API and OpenCV library. However, the model accuracy was good despite a small training set. It is also possible that, with such a small dataset, you might not get any predictions for a given class. This can be further improved by adding more images to each class, or training the model under different lightings and environments.