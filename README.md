# Time_Frequency_Analysis

This repository contains code for an Time Frequency analysis of random time data with 50 trials. The code includes various steps for processing the data, such as:

- Window function: Applying a window function to the data to reduce spectral leakage. Common window functions include the Hanning, Hamming, and Blackman windows.

- STFT: This step involves taking the Fourier transform of small, overlapping segments of the data, known as "frames," to estimate the frequency content at each point in time.

- Spectrogram: The output of the STFT is often displayed as a spectrogram, which is a three-dimensional representation of the frequency content of the signal as a function of time.

- Data visualization: The spectrogram is often visualized using a heatmap, where the color represents the amplitude of the frequency content at each point in time.

![ff562104-7ffd-4ab5-a651-af243d004e5f](https://user-images.githubusercontent.com/60902991/212781411-4336ebef-1d17-4a2d-84c6-1b8cac541623.png)
