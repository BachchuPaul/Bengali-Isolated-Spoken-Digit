﻿# Bengali (Bangla) Speech Recognizer
Here the spoken Bengali digits (almost 13554 audio files) have been recognized by a CNN from Mel Frequency Cepstral Coefficients (MFCC), Spectral Sub-band Energy (SSE), and Log Spectral Sub-band Energy (LSSE).
The audio clips are cropped into one second by removing noise and silence for the clips for more than one second. And the clips of less than one second are padded with zero amplitude to make into one second.
Another dataset, audio-MNIST (30000 audio clips in English spoken digits) have been used in the study. We have extracted the feature for the Bengali dataset into 'XFull_Bengali.csv' file and Mnist-audio dataset into 'XFull_MNIST.csv' file. The CSV files hold each audio sample's 1860 features in a row. Since these CSV files are greater than 25MB, the audio files can be accessed using a request to this email: ableb.paul@gmail.com
If any part of the code or data is used, please cite our paper: 
