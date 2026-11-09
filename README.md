# Pothole Detection with Neural Networks

Binary classification of road images (normal road vs. pothole) comparing a fully connected network, two convolutional neural networks, and a VGG16-style network, built in TensorFlow/Keras. The project also includes classical image filter visualizations and a DCGAN trained to generate synthetic pothole images.

## Results

| Model | Test Set Accuracy |
| FCN   | 87.6%             |
| CNN1  | 96.5%             |
| CNN2  | 97.7%             |
| VGG16 | 96.6%             |

See results/ for training and validation accuracies. See pothole-detection-notebook for final test set accuracies for each model.

dataset-samples/ contains samples of images from the dataset shown as ground truth, along with corresponding filtering applied to the images.

## Dataset

Source: Nomal-Pothole-dataset, Neha Tanwar (Researcher), 2024. https://zenodo.org/records/13334878
