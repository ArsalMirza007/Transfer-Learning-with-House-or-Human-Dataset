# Transfer-Learning-with-House-or-Human-Dataset

# Instructions:
Tasks performed in the provided code:

1. **Downloading Dataset**: The code downloads the Horse or Human dataset, which contains images of horses and humans, and extracts it into the appropriate directories for training and validation.

2. **Preparing Directories and Checking Dataset**: It sets up directories for training and validation data and checks the number of images available for each class (horses and humans) in both the training and validation sets.

3. **Visualizing Sample Images**: It displays sample images of horses and humans from the dataset to give an idea of what the data looks like.

4. **Setting up Image Data Generators**: It sets up generators for training and validation data, using `ImageDataGenerator` from Keras to perform data augmentation and normalization. These generators will be used to feed batches of images into the neural network during training.

5. **Downloading Pre-trained InceptionV3 Model**: The code downloads the pre-trained weights for the InceptionV3 model, which will be used for transfer learning.

6. **Creating Pre-trained Model**: It initializes an InceptionV3 model with pre-trained weights, making all layers non-trainable. This model will serve as the base for transfer learning.

7. **Setting up Callbacks**: It defines a custom callback class that stops training once the desired accuracy (99.9%) is reached.

8. **Extracting Output of Last Layer**: It retrieves the output of the last layer of the pre-trained model, which will serve as input to the new classification layers.

9. **Creating Final Model**: It creates the final model by adding custom classification layers on top of the pre-trained InceptionV3 model using the Functional API. The model is compiled with appropriate loss function, optimizer, and evaluation metrics.

These tasks collectively set up the environment, prepare the data, define the model architecture, and establish training settings for performing transfer learning on the Horse or Human dataset.

# Screenshots:
![Screenshot (12)](https://github.com/ArsalMirza007/Transfer-Learning-with-House-or-Human-Dataset/assets/121928372/b0b426d2-2bd0-4162-b120-62ea91131960)
![pic](https://github.com/ArsalMirza007/Transfer-Learning-with-House-or-Human-Dataset/assets/121928372/791ee518-ecc8-447c-bd19-77022024ffd8)

