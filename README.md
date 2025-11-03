# Galaxy10 DECaLS Convolutional Neural Network Classifier

This project is the result of a lot of experimentation to find a minimal CNN architecture for classifying images of galaxies from the Galaxy10 DECaLS dataset. I have been able to get over 70% accuracy using this relatively simple model in my own tests, and theoretically you should be able to get similar results since I have included a seed for the randomness. In order to run it yourself, you will need to download the h5 file of the dataset here: https://astronn.readthedocs.io/en/latest/galaxy10.html

To make it runnable on my laptop, I used a stratified and random subset of the dataset for training, validating, and testing. You may need to install a few dependencies, such as Keras and h5py. All imports are in the first cell, so they should be easy to identify. 
