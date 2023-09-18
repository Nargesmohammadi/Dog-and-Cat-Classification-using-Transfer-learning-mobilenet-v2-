
# Dog and Cat Classification using Transfer Learning MobileNet-V2 🐶🐱

This repository contains code for a Dog and Cat Classification model using transfer learning with MobileNet# Dog and Cat Classification using Transfer Learning MobileNet-V2

This GitHub repository contains code for a dog and cat classification project using transfer learning with MobileNet-V2. The goal of this project is to train a model that can accurately classify images of dogs and cats.

## Dataset

The dataset used for this project can be found [here](https://www.kaggle.com/competitions/dogs-vs-cats/rules). It consists of a collection of labeled dog and cat images. 

## Code

The code in this repository includes the following steps:

1. Counting the number of files in the training folder.
2. Displaying some sample images from the dataset.
3. Resizing and saving the images in a separate folder.
4. Assigning labels to the resized images.
5. Checking the distribution of dog and cat images.
6. Loading and preprocessing the images.
7. Defining the MobileNet-V2 model with a dense classification layer.
8. Compiling and training the model.
9. Evaluating the model on the test set.
10. Using the trained model to make predictions on custom images.


## Requirements

The following libraries are required to run the code:

- Numpy
- PIL
- Matplotlib
- Scikit-learn
- OpenCV
- TensorFlow
- TensorFlow Hub
- Glob

You can install the required libraries using `pip` or `conda` package managers.

```bash
pip install numpy pillow matplotlib scikit-learn opencv-python tensorflow tensorflow-hub
```

## Acknowledgments

- The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/competitions/dogs-vs-cats/rules).
- The MobileNet-V2 model used for transfer learning is obtained from the TensorFlow Hub.

You can see the results of the code for classifying Dog vs Cat images:

![image](https://github.com/Nargesmohammadi/Dog-and-Cat-Classification-using-Transfer-learning-mobilenet-v2-/assets/96385230/2733e5ff-6156-458a-95e4-6f21d56f42e0)
![image](https://github.com/Nargesmohammadi/Dog-and-Cat-Classification-using-Transfer-learning-mobilenet-v2-/assets/96385230/3ef48edd-cec5-4534-b581-5f8fbc06586d)



