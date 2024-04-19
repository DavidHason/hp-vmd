# hp-vmd
# Advanced Speech Emotion Recognition (ASER)

## Overview
This repository contains the implementation of Advanced Speech Emotion Recognition using Mel spectrogram Harmonic-Percussion Component with Variational Mode Decomposition (HP-VMD). This project integrates Harmonic-Percussion Component Analysis (HPCA) and Variational Mode Decomposition (VMD) to enhance the accuracy and sensitivity of emotion detection systems from speech signals.

## Project Description
The ASER system is designed to address the limitations of traditional speech emotion recognition (SER) systems, which largely rely on individual feature extraction methods. By synergistically combining HPCA and VMD, our method refines feature extraction, ensuring robustness and higher accuracy in emotion classification. The integration of these techniques allows for the precise extraction of nuanced acoustic features from speech signals, making the emotion recognition process more effective and sensitive to subtle emotional expressions.

## Main Features
Harmonic-Percussive Component Analysis (HPCA) separates the harmonic and percussive elements of audio signals, enhancing the clarity and distinction of voice tones and temporal dynamics crucial for emotion recognition.
Variational Mode Decomposition (VMD) optimizes the decomposition of speech signals into adaptively determined modes, reducing information loss and improving the representation of emotional features.
- CNN-Based Classification: This method utilizes a Convolutional Neural Network (CNN), specifically the VGG16 model, to classify emotions based on the extracted features.
Comprehensive Feature Set: This set employs Mel-frequency cepstral coefficients, Chromagrams, Mel spectrograms, Tonnetz diagrams, and spectral centroids to create multidimensional feature vectors.

## Results
Our initial experiments conducted on the Berlin EMO-DB database have demonstrated a state-of-the-art classification accuracy of 96.67%, significantly surpassing traditional SER methods.

## Usage
Detailed instructions for setting up the project, running the code, and replicating the experiments are provided. Users can train the model with their datasets or test the pre-trained models with provided audio samples.

## Contributions
Contributions are welcome! If you would like to improve the codes, add functionalities, or improve the docs, please feel free to make a pull request.

## License
This project is open-sourced under the MIT license. See the LICENSE file for details.

## Citation
If you find this work useful in your research, please consider citing:
will be available after the paper is published. 
