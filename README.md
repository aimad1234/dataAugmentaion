# Albumentation Data Augmentation

This repository contains code for performing data augmentation using the Albumentations library in Python. It includes functions to visualize bounding boxes on images, read and save bounding box labels in YOLO format, and apply transformations to images and bounding boxes using Albumentations.

## Installation

To use the code in this repository, you need to install the required dependencies. Run the following command to install the `albumentations` library:

```shell```
!pip install albumentations
## Usage

The code in this repository provides several functions for data augmentation:

- `visualize_bbox`: This function visualizes a single bounding box on an image.
- `visualize`: This function visualizes multiple bounding boxes on an image.
- `read_file_txt`: This function reads bounding box labels from a text file.
- `Transformation`: This function applies transformations to an image and its corresponding bounding boxes.
- `save_labels`: This function saves transformed bounding box labels to a text file.
- `augmentation_data`: This function performs data augmentation on a set of images and their bounding box labels.

Please note that the usage instructions provided here assume that the reader is familiar with Python programming and has the necessary knowledge to use the functions in the code.

To use these functions, you need to provide the paths to the source images and labels, as well as the destination paths for the augmented images and labels. Modify the following variables in the code to match your directory structure:

```python```
source_images = "your folder images src"
source_labels = "your folder labels src"
destination_images = "your folder images des"
destination_labels = "your folder labels des"

To augment the data, call the `augmentation_data` function with the appropriate source and destination paths:
augmentation_data(source_images, source_labels, destination_images, destination_labels)


