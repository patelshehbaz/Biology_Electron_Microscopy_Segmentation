# Title: Electron Microscopy Image Segmentation using U-Net

Goal:

The primary goal of this project is to develop a machine learning model that can effectively segment specific structures within electron microscopy images. Segmentation involves identifying and delineating regions of interest (ROI) within the images, such as cellular components or other biological structures.

## Data

[Dataset](https://www.kaggle.com/datasets/dat0chin/electron-microscopy-dataset)
The project utilizes a dataset of electron microscopy images paired with corresponding masks. These masks are essentially annotations that outline the structures of interest within each image. The data is split into two sets:

- Training Set: Used to train the machine learning model, helping it learn to predict the segmentation masks from the images.
- Testing Set: Used to evaluate the model's performance, ensuring that it generalizes well to new, unseen data.
