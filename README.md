# image-classification-with-MobileNetV2
Code for an image classification model using MobileNetV2

# Image Classification: Deer vs Badger 🦌🦡

This project demonstrates a binary image classification model to differentiate between images of deer and badgers. The model was built using TensorFlow and Keras, with MobileNetV2 as the backbone architecture.

# Project Overview
I created this project out of a personal interest in wildlife and artificial intelligence. Over the years, I’ve set up camera traps to observe and photograph wildlife in their natural habitats. This has fueled my curiosity about using AI to analyze these images, identifying species automatically and potentially gaining insights from the captured data.

After testing custom-built models, I decided to use a pre-trained model for this project to leverage the strength of transfer learning, particularly given the limited size of my dataset. With MobileNetV2, a lightweight architecture optimized for smaller datasets, the model adapts pre-existing features learned from the ImageNet dataset to help distinguish between two classes: Roe deer and Badger.

This project allowed me to explore transfer learning for a personal wildlife camera trap dataset, merging my passion for nature with my interest in machine learning. The use of MobileNetV2 with transfer learning helped overcome the constraints of a small dataset while achieving promising results.

## Project structure

- **notebook.ipynb**: The Jupyter notebook with full code to train and evaluate the model.
- **data.zip**: Google link to the folder containing the deer and badger images: https://drive.google.com/file/d/1oYzWo4DQKMj3NjkCbeYrREjbXJhUZWsp/view?usp=sharing  

## Code execution

1. **Install dependencies**: Make sure you have Python and TensorFlow installed.
2. **Launch Notebook**: Run `MobileNetV2_roe_badger_google.ipynb` to train and evaluate the model.

## Author

Project created by [Mattéo Schweizer].

## License

This project is licensed under the MIT License.
