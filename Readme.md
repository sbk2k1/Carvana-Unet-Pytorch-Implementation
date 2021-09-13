Implementation of U-net architecture

Description:-


i. model.py contains the Unet model implemented in pytorch

ii. Train.py handles the training.

iii. dataset.py creates the dataset class and creates the respective dataloaders.

iv. utils.py has utility functions for example augmentation and accuracy/dice coefficients/calculation


Some points to be kept in mind:

i. I could not train the model due to limitations in computational resources and because google colab cannot install        
   albumentations library.

ii. Images as they are predicted will be saved in Prediction_example folder

iii. Model will be saved in "my_checkpoint.pth.tar"

iv. Data can be downloaded from <a href="https://www.kaggle.com/c/carvana-image-masking-challenge">Here</a>

v. Only 5040 training and 48 testing/validation images are used