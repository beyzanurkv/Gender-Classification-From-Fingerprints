
Gender Classification from Fingerprints
This Notebook implements a CNN model to predict gender from fingerprint images using the SOCOFing dataset on Kaggle.

Features
- Loads and preprocesses fingerprint images from Real, Altered-Easy, Altered-Medium, and Altered-Hard sets.

- Extracts gender labels from filenames (M/F).

- Builds a deep CNN with Conv2D, MaxPooling, Dropout, and Dense layers.

- Trains for 20 epochs with Adam optimizer and binary crossentropy loss.

Dataset
- Uses SOCOFing dataset with 6,000 real and altered fingerprints labeled by gender and finger type.


Results
- Model achieves high accuracy (~95-99%) on test data after training; training/validation plots included.

Note: Adapted from a course assignment based on amanxai.com tutorial.

