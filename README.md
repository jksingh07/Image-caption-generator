# Image Caption Generator

The Image Caption Generator project aims to develop software that can generate descriptive captions for images using neural networks language models. It involves dual techniques from computer vision to understand the content of the image and a language model from the field of natural language processing to turn the understanding of the image into words in the right order.

## Functionality

This web application performs the following functions:

- **Image Captioning**: Recognising different types of objects in an image and creating a meaningful sentence that describes that image to visually impaired persons.
- **Text to Speech Conversion**: Converting the generated sentence into audio form for easy access to the visually impaired.

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

## Acknowledgments

The authors would like to thank the creators of TensorFlow, Keras, and Flask for their contributions to the open-source community.
