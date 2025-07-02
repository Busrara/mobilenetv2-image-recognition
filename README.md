# mobilenetv2-image-recognition

This project implements a binary image classification model to distinguish cats from dogs by transfer learning with MobileNetV2.

The dataset is sourced from [Kaggle’s Cat and Dog Dataset](https://www.kaggle.com/datasets/tongpython/cat-and-dog). The model is first trained with frozen base layers for feature extraction, then fine-tuned by unfreezing the last layers for higher accuracy.

## Features
- Uses TensorFlow and Keras
- Employs data augmentation and validation split
- Achieves 0.9801 validation accuracy after fine-tuning
- Includes code for testing new images with visualization

## How to Use
1. Download or clone the repo.
2. Upload your Kaggle API credentials (`kaggle.json`).
3. Run the notebook on Google Colab or locally.
4. Test the model with your own images.

---

Feel free to contribute or report issues :)
