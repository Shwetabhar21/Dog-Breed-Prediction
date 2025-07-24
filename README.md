## 🐶 Dog Breed Prediction

A deep learning project to classify dog breeds from images using TensorFlow/Keras.

## Features
- Image classification using CNN
- Trained on dog breed dataset
- Model achieves high accuracy on validation data
- Simple and customizable architecture

## Requirements
- Python 3.8+
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

Install dependencies:
```bash
pip install -r requirements.txt
````

## How to Use

1. Place images in `dataset/` folder with subfolders per breed.
2. Run `Dog_Breed_Prediction.ipynb` to:

   * Preprocess and split data
   * Train the CNN model
   * Evaluate and predict dog breeds

## Structure

* `Dog_Breed_Prediction.ipynb` — Main notebook
* `dataset/` — Images organized by breed
* `model.h5` — Trained model (optional output)
* `requirements.txt` — Required packages
