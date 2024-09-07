# Mental Workload Estimation Using Deep Learning

This repository contains code for estimating Mental Workload (MWL) using deep learning methods, specifically Convolutional Neural Networks (CNN) combined with Long Short-Term Memory (LSTM) networks, along with brain effective connectivity analysis.

## Project Overview

Mental Workload (MWL) is a vital aspect of cognitive psychology and human-computer interaction. By leveraging advanced deep learning techniques and brain effective connectivity, we aim to create a robust model for accurately assessing MWL from EEG signals.

## Key Features

- **Deep Learning Architecture**: Utilizes a hybrid model combining CNNs and LSTMs to capture spatial and temporal patterns in EEG data.
- **Effective Connectivity Analysis**: Incorporates brain effective connectivity to enhance the understanding of inter-regional brain interactions.
- **Dataset**: The project uses the STEW dataset, which contains labeled EEG recordings for training and validation.

## Methodology

![method](./files/CNN+LSTM%20Block%20diagram.drawio.png)

1. **Data Preprocessing**: EEG signals are preprocessed to extract relevant features and prepare them for input into the deep learning model.
2. **Model Architecture**:
   - **CNN**: Extracts spatial features from the EEG signals.
   - **LSTM**: Captures temporal dependencies in the data.
3. **Training and Evaluation**: The model is trained on the preprocessed data and evaluated for its performance in predicting MWL levels.

## Sample Connectivity Image
![Sample Image](./files/high%20theta.png)

## Published Paper:
https://www.tandfonline.com/doi/full/10.1080/10255842.2024.2386325