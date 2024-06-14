### Flower Image Classifier with Augmentation and Transfer Learning
In this project, we'll be creating a deep learning network to classify flowers per the labels provided. This project was established by Udacity and performed within Udacity's GPU enabled workspace, so unfortunately the source files for this project are not included. The project also utilizes transfer learning to import already trained classifiers from the PyTorch package while modifying the classifier attribute of each package.

### Project Breakdown
The files work through the project in the following manners:
 - **Creating the Datasets**: Utilizing the images provided by Udacity, the first part of the project looks to import the data while applying proper transforms and segmenting them into respective training, validation, and testing datasets
 - **Creating the Architecture**: Utilizing the pre-trained models from PyTorch's torchvision package, we establish different classifier paramaters to fit our datasets as well as establishing an NLL Loss criterion and Adam optimizer
 - **Training the Model**: With help from PyTorch and Udacity's GPU-enabled platform, we train our model across our training and validation datasets to create an ideal model for classifying the flowers.
 - **Saving / Loading the Model**: To practice utilizing the model in other platforms, we export the model to a 'checkpoint.pth' file and re-load / rebuild it in another file.
 - **Class Prediction**: Finally, we use our newly trained model to make a prediction of a flower given a testing input image.

### Files Included
These are the files included as part of the project and what each contains:
 - flowers_with_data_augmentation.ipynb
 - flowers_with_transfer_learning.ipynb
