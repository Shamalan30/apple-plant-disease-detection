# Apple Plant Disease Detection

A deep learning project focused on classifying apple leaf images into different disease categories using Convolutional Neural Networks (CNN) and transfer learning.

## Project Overview

This project explores image classification for identifying apple leaf conditions using TensorFlow and Keras. It implements a custom CNN and MobileNetV2 to explore different approaches to image-based plant disease classification.

## Objectives

* Explore deep learning for plant disease image classification.
* Implement a custom Convolutional Neural Network (CNN).
* Apply transfer learning using MobileNetV2.
* Visualize model training and evaluation results.
* Generate predictions for individual leaf images.

## Disease Categories

The project covers four categories:

* Apple Scab
* Apple Black Rot
* Cedar Apple Rust
* Healthy Apple Leaves

## Technologies Used

* Python
* TensorFlow
* Keras
* TensorFlow Datasets
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Models Implemented

### 1. Custom CNN

A convolutional neural network developed for image classification.

### 2. MobileNetV2

A pretrained convolutional neural network explored through transfer learning and fine-tuning.

## Dataset

The project uses the PlantVillage dataset accessed through TensorFlow Datasets. The notebook selects apple leaf image categories relevant to this classification task.

The dataset is not included in this repository.

## Project Structure

```text
apple-plant-disease-detection/
├── README.md
└── apple_plant_disease_detection.ipynb
```

## How to Run

1. Clone or download this repository.
2. Open the Jupyter notebook in Google Colab or a compatible Jupyter environment.
3. Run the notebook cells in sequence.
4. Allow the required libraries and dataset to be installed or downloaded when prompted.

Note: Execution time and results may vary depending on the hardware, library versions, and runtime environment.

## Limitations

This project explores classification using a curated image dataset. Performance on real-world photographs may differ because of lighting, background, camera quality, and variations in leaf appearance.

Predictions should be treated as model outputs for educational and experimental purposes rather than definitive agricultural diagnoses.

## Future Improvements

* Evaluate the model using independently collected field images.
* Explore deployment through a web or mobile application.
* Investigate model optimization for edge devices.

## Author

Shamalan A/L Vellu Thavar

## Disclaimer

This project is intended for educational and learning purposes.
