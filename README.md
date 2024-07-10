# Image Classification with PyTorch

This repository contains the code and instructions for implementing an image classification model using PyTorch on a custom dataset.

## Dataset Details
- **Total Images:** 5000
- **Number of Classes:** 10
- **Image Resolution:** 64x64

## Data Splits
- **Training Set:** 3000 images
- **Validation Set:** 500 images
- **Test Set:** 1500 images

**CSV Columns:**
- `image_name`: Name of the image
- `image_path`: Relative path to the image
- `class_id`: ID of the class the image belongs to (not in test CSV)
- `class_name`: Name of the class the image belongs to (not in test CSV)

## Provided Resources
A Jupyter notebook is provided with:
- Code for downloading the data
- Basic dataloaders
- Helper functions

## Tasks
1. **Train your model**: Implement and train your image classification model on the training set.
2. **Evaluate your model**: Test your model on the validation set and make adjustments as necessary.
3. **Generate Predictions**: Once trained, generate predictions on the test set and save them in `prediction.csv`.

## Submission Instructions
1. **Prediction File**: Upload `prediction.csv` to Gradescope.
2. **Notebook PDF**: Upload a PDF of your notebook showing your work and results.

**Note**: Ensure that the prediction file includes all test images and required columns. Do not modify the cell where predictions are dumped to avoid submission errors.

## Additional Logistics
- You may work individually or in groups (preferably your project groups).
- You are allowed up to 50 submissions.
- Final submission must include both the prediction file and the PDF of the notebook.

Ensure all submissions adhere to the instructions to be graded correctly by the autograder. Happy coding!


