# Image Classification: Cats, Dogs, Snakes

This project implements an image classification model to categorize images into 3 classes: `cats`, `dogs`, and `snakes`. The model uses VGG16 with transfer learning, achieving a target accuracy of ≥85% on validation and test sets. The code is designed to run on Google Colab using a dataset stored in Google Drive.

## Project Overview
- **Objective**: Classify images into `cats`, `dogs`, or `snakes` with ≥85% accuracy.
- **Dataset**: 3,000 images (1,000 per class) from kaggle, stored in Google Drive, with subfolders `cats`, `dogs`, and `snakes`.
- **Model**: VGG16 pre-trained on ImageNet, fine-tuned with 4 layers unfrozen.
- **Environment**: Google Colab Free (T4 GPU).
- **Output**: Trained model in SavedModel, TFLite, and TFJS formats, accuracy/loss plots, and inference results.

### Results
- **Training Accuracy**: ~94.21%
- **Validation Accuracy**: ~87.00%
- **Testing Accuracy**: ~91.00%
- **Training Time**: ~25-35 minutes for 5 epochs.

## Prerequisites
- **Google Colab Account**: Required to run the notebook.
- **Google Drive**: Dataset must be stored in Google Drive.
- **GPU**: Enable T4 GPU in Colab (`Runtime > Change runtime type > Hardware accelerator > GPU`).
- **Dependencies**: Install required packages (see Installation).
