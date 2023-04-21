# Bengali Speech Recognizer
Here the spoken Bengali digits have been recognized by a CNN from Mel Frequency Cepstral Coefficients (MFCC), Spectral Sub-band Energy (SSE) and Log Spectral Sub-band Energy (LSSE).
The audio clips are cropped into one second by removing noise and silence for the clip more than one second. And the clips less than one second are padded with zero amplitude to make into one second.
We have extracted the feature for the Bengali dataset into 'XFull_Bengali.csv' file and Mnist-audio dataset into
