# Audio Signal Processing and Phoneme Segmentation
=====================================================

## Table of Contents
-----------------

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)

## Introduction
---------------

This project focuses on audio signal processing and phoneme segmentation using various techniques such as Non-negative Matrix Factorization (NMF), Dynamic Time Warping (DTW), and SHAP (SHapley Additive exPlanations) for feature importance.

## Features
------------

*   **Audio Preprocessing**: Loads audio files, applies noise reduction, and generates spectrograms.
*   **NMF for Phoneme Segmentation**: Applies NMF to spectrograms for phoneme segmentation.
*   **DTW for Refining Boundaries**: Refines phoneme boundaries using DTW.
*   **SHAP for Feature Importance**: Explains feature importance using SHAP values.
*   **Word Boundary Detection**: Detects word boundaries based on zero-crossing rate and short-term energy.
*   **Phoneme Playback**: Plays back detected phonemes.

## Requirements
---------------

*   Python 3.x
*   Librosa
*   NumPy
*   Matplotlib
*   Scikit-learn
*   SHAP
*   IPython

## Installation
---------------

To install the required libraries, run the following command:

```bash
pip install librosa numpy matplotlib scikit-learn shap
```
------------
## Usage
* Load an audio file using librosa.load().
* Preprocess the audio using the preprocess_audio() function.
* Apply NMF to the spectrogram using the apply_nmf() function.
* Refine phoneme boundaries using DTW with the refine_boundaries() function.
* Explain feature importance using SHAP with the explain_segmentation() function.
* Detect word boundaries using the harness() function.
* Play back detected phonemes using the play_phonemes() function.

------------

## Contributing
Contributions are welcome. To contribute, please fork this repository, make your changes, and submit a pull request.
