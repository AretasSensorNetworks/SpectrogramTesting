# Spectrogram Testing #

The Aretas platform has the ability to ingest acoustic and vibration data from thousands of Aretas IoT monitors deployed in various customer applications. 

We can classify the data  in the platform and generate spectrograms from the data packets and export the labeled spectrograms for model training and deployment. The spectrograms in the platform can support:
- Overlapping
- Arbitrary sample rates
- Interpolation 
- Resizing
- Multiple pallettes

For this experiment, we produced low-sample rate data of different individuals saying "cat" or "dog" and produced confounder test data of different words that sounds like "cat" (sand, ae, family, etc.) All test, training and validation data was specifically downsampled to 8kHz (16-bit) for more challenging classification. 
