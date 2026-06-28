# Berry Image Recognition

A convolutional neural network (CNN) based image recognition project for classifying Nordic berries.

## Overview
This project uses deep learning to classify images of six Nordic berry types, comparing the performance of different recurrent neural network architectures (LSTM, BiLSTM, and GRU) combined with CNN feature extraction.

## Berry Categories
- Blackberries (Björnbär)
- Blueberries (Blåbär)
- Cloudberries (Hjortron)
- Lingonberries
- Raspberries (Hallon)
- Swedish Red Currant

## Project Structure
- `images_cnn.ipynb` — Main Jupyter notebook containing the model training and evaluation
- `image_recog/data_berries/` — Image dataset organised by berry category

## Requirements
- TensorFlow
- Pillow (PIL)
- NumPy
- Matplotlib
- scikit-learn (for `confusion_matrix` and `ConfusionMatrixDisplay`)
