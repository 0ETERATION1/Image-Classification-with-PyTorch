# Image Classification with PyTorch

Welcome to my image classification project! In this repo, I've implemented an image classification model using PyTorch on a custom dataset.

## Dataset Overview
I worked with a dataset consisting of 5000 images, each with a resolution of 64x64 pixels. The dataset is divided into 10 classes.

### Data Splits
- **Training Set:** 3000 images
- **Validation Set:** 500 images
- **Test Set:** 1500 images

### Dataset Structure
After downloading the dataset from the data.tar.gz file, I organized it as follows:


Each CSV file contains:
- `image_name`: Name of the image
- `image_path`: Relative path to the image
- `class_id`: ID of the class the image belongs to (except in the test set)
- `class_name`: Name of the class the image belongs to (except in the test set)

## Project Details
In the provided Jupyter notebook, I included code for:
- Downloading the data
- Setting up basic dataloaders
- Helper functions to streamline the process

### Model Training
I implemented and trained the image classification model on the training set. I used the validation set to evaluate the model and make necessary adjustments to improve performance.

### Generating Predictions
After training, I tested the model on the test set. The predictions were saved in a file named `prediction.csv`.

Thanks for checking out my project! Feel free to explore the notebook to see how I approached building the image classification model.
