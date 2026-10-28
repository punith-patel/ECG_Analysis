# ECG Analysis & Arrhythmia Detection

A deep learning-based ECG arrhythmia classification and analysis web application built with PyTorch, Torchvision (ResNet-18), and Flask.

## Features
- **Deep Learning Model**: ResNet-18 architecture fine-tuned for ECG heartbeat classification.
- **MIT-BIH Arrhythmia Dataset**: Classifies ECG signals into categories (e.g., Normal, Premature Ventricular Contraction, Supraventricular Premature, Fusion of Ventricular and Normal, Unclassifiable Beat).
- **Web Application**: Interactive Flask frontend for uploading ECG samples, visualizing waveforms, and getting real-time predictions with confidence scores.
- **Training Pipeline**: Script to train, validate, and evaluate the CNN model.

## Installation

```bash
# Clone the repository
git clone https://github.com/punith-patel/Ecg-analysis.git
cd Ecg-analysis

# Install dependencies
pip install -r requirements.txt
```

## Running the Application

```bash
python app.py
```
Open your browser at `http://127.0.0.1:5000` to interact with the ECG analysis tool.

## Dataset & Training

To prepare data and train the model:
```bash
python prepare_data.py
python train_cnn.py
```
