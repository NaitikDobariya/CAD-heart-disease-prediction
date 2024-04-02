# CAD-heart-disease-prediction

## Coronary Artery Disease Detection Using ECG Data

This repository presents an attempt to replicate the results of a research paper focusing on the detection of Coronary Artery Disease (CAD) using electrocardiogram (ECG) data. Please note that this project is a replication effort and does not constitute an original discovery.

### About the Project

The project aims to investigate the feasibility of detecting CAD using ECG data, with potential applications in wearable technology such as smartwatches. The research paper referenced for this project provides insights into the methodology and data used. The dataset utilized comprises ECG recordings from both healthy individuals and those diagnosed with CAD, as detailed in the cited paper. Extensive data preprocessing was conducted, adhering to the procedures outlined in the paper.

The model architecture implemented in this project is a 1D convolutional neural network (CNN)-based classifier, which was replicated based on the methodology described in the paper.

### Research Paper Reference

The research paper titled "Coronary Artery Disease Detection using ECG Signals" can be accessed via the following link: [Paper Link](https://doi.org/10.1016/j.compbiomed.2017.12.023)

### Libraries Used

The project leverages the following libraries for implementation:

- TensorFlow
- NumPy
- WFDB (WaveForm Database library)
- PyWavelets
- Pandas
- Scikit-learn
- Matplotlib

### Results

The model achieved a validation accuracy of approximately 96%, which is slightly lower than the reported accuracy in the paper. Below are the training and accuracy curves:

![6d248c65-f398-4d0d-8744-7ab89ff3144a](https://github.com/NaitikDobariya/CAD-heart-disease-prediction/assets/113834773/e777fde9-16f5-4647-8acd-13f0dd7d9811)

![ef981137-8dd3-4d28-82ef-81af43cf8002](https://github.com/NaitikDobariya/CAD-heart-disease-prediction/assets/113834773/88f5e112-007a-4b9b-8fec-48026c3b0c9a)

Thank you for your attention.
