# Audio Scene Classification

***This repository contains the code for project "Audio Scene Classification". This project uses audio in the nearby environment to classify the things in a scene without using a visual component.***

# Requirements

**1. Python 3.6**

**2. Librosa 0.6 [Audio Processing Library]**

```
pip3 install librosa --upgrade
```

**3. Matplotlib**

```
pip3 install matplotlib --upgrade
```

**4. Keras**

```
pip3 install keras --upgrade
```

**5. Tensorflow**

```
pip3 install tensorflow --upgrade
```

or 

```
pip3 install tensorflow-gpu --upgrade
```

**NOTE: Tensorflow GPU requires CUDA and cuDNN.**

**6. Pickle**

```
pip3 install pickle --upgrade
```

# Dataset

The dataset I am using for this project is the "UrbanSound dataset".

Download the dataset from the link below and place inside the dataset folder.

```
https://serv.cusp.nyu.edu/projects/urbansounddataset/
```

# Extracted Audio Features

The main extracted features from the audio are:

**a). Mel Spectrogram:** Mel-scaled Power Spectrogram

**b). MFCC:** Mel-Frequency Cepstral Coefficients

**c). Chorma STFT:** Compute a chromagram from a waveform or power spectrogram

**d). Spectral Contrast**: Compute spectral contrast

**e). Tonnetz:** Computes the tonal centroid features (tonnetz)

*Following are the extracted features for some audio files:*

**1. Air Conditioner Audio Features**

<img src="Outputs/air conditioner_features.jpg" alt="" width="100%">

**2. Car Horn Audio Features**

<img src="Outputs/car horn_features.jpg" alt="" width="100%">

**3. Children Playing Audio Features**

<img src="Outputs/children playing_features.jpg" alt="" width="100%">

**4. Dog Barking Audio Features**

<img src="Outputs/dog bark_features.jpg" alt="" width="100%">

**5. Idle Engine Audio Features**

<img src="Outputs/engine idling_features.jpg" alt="" width="100%">
