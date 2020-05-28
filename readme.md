# Python Mini Project – Speech Emotion Recognition
# Packages/libraries

# Librosa
LibROSA is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.

# Soundfile
SoundFile represents audio data as NumPy arrays.

# os
This module provides a portable way of using operating system dependent functionality.

# Global
Usually, the programmers require to traverse through a list of files at some location, mostly having a specific pattern. Python’s glob module has several functions that can help in listing files under a specified folder.

# scikit-learn
Machine Learning in Python

# NumPy’s main object is the homogeneous multidimensional array.
It is a table of elements (usually numbers), all of the same type, indexed by a tuple of non-negative integers. 


Define a function extract_feature to extract the mfcc, chroma, and mel features from a sound file. This function takes 4 parameters- the file name and three Boolean parameters for the three features:

    mfcc: Mel Frequency Cepstral Coefficient, represents the short-term power spectrum of a sound
    chroma: Pertains to the 12 different pitch classes
    mel: Mel Spectrogram Frequency