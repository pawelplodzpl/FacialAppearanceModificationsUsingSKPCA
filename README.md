# Facial Appearance Modifications using SKPCA-Derived Features Extracted from Convolutional Autoencoder's Latent Space

labels.csv - contains additional information about images from the Celeb data set.

The project has been divided into six parts

1. Training CAE on Celeb data set.
2. Encoding images using trained CAE and merging it with labels
3. Choosing the representative part of the collection to learn SKPCA 
4. Calculating SKPCA
5. Calculating Inverse of SKPCA
6. Sample images modyfication based on SKPCA + CAE model 
