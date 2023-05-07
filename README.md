# Image Caption Generator

## Introduction
The basic working of the project is that the features are extracted from the images using pre-trained VGG16 model and then fed to the LSTM model along with the captions to train. The trained model is then capable of generating captions for any images that are fed to it.

The Image Caption Generator project aims to develop software that can generate descriptive captions for images using neural networks language models. It involves dual techniques from computer vision to understand the content of the image and a language model from the field of natural language processing to turn the understanding of the image into words in the right order.

## Functionality

This web application performs the following functions:

- **Image Captioning**: Recognising different types of objects in an image and creating a meaningful sentence that describes that image to visually impaired persons.
- **Text to Speech Conversion**: Converting the generated sentence into audio form for easy access to the visually impaired.


## Dataset
The dataset used here is the FLICKR 8K which consists of around 8091 images along with 5 captions for each images. If you have a powerful system with more than 16 GB RAM and a graphic card with more than 4 GB of memory, you can try to take FLICKR 30K which has around 30,000 images with captions.

## Applications

Image captioning has various applications such as:

1. Recommendations in editing applications
2. Usage in virtual assistants
3. Image indexing
4. For visually impaired persons
5. Social media
6. Several other natural language processing applications.

At present, images are annotated with human intervention, and it becomes a nearly impossible task for huge commercial databases. The image database is given as input to a deep neural network (Convolutional Neural Network (CNN)) encoder for generating “thought vector” which extracts the features and nuances out of our image and RNN (Recurrent Neural Network) decoder is used to translate the features and objects given by our image to obtain a sequential, meaningful description of the image.

This project can act as a vision for visually impaired people, as it can identify nearby objects through the camera and give output in audio form. The application can provide a highly interactive platform for specially-abled people.


## Technologies Used

- Python
- TensorFlow
- Keras
- Flask

## Installation

To install and run this project locally, follow these steps:

- Clone this repository
- Navigate to the project directory
- Install dependencies by running `pip install -r requirements.txt`
- Run the application by running `python app.py`
- Open a web browser and navigate to http://localhost:5000

## Train Data Samples
![Train Data Samples](https://github.com/jksingh07/Image-caption-generator/blob/main/Results/train.png)

# Results
![Result without BLEU score](https://github.com/jksingh07/Image-caption-generator/blob/main/Results/result.png)
![Final Results](https://github.com/jksingh07/Image-caption-generator/blob/main/Results/result2.png)
![Final Results](https://github.com/jksingh07/Image-caption-generator/blob/main/Results/result3.png)

## Acknowledgments

The authors would like to thank the creators of TensorFlow, Keras, and Flask for their contributions to the open-source community.
