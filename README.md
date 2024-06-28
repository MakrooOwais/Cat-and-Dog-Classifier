# Cat vs Dog Image Classifier using PyTorch

This project implements a convolutional neural network (CNN) in PyTorch to classify images of cats and dogs. It includes data preprocessing, model training, evaluation, and visualization of results.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
4. [Folder Structure](#folder-structure)
5. [Training and Evaluation](#training-and-evaluation)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Overview

This repository contains Python scripts and Jupyter notebooks to build and train a deep-learning model that classifies images as cats or dogs. It includes:

- **Dataset:** The project uses the Cats and Dogs dataset, consisting of images of cats and dogs for training, validation, and testing.

- **Model Architecture:** Implemented a custom CNN architecture using PyTorch's nn.Module.

- **Training:** Trained the model using Adam optimizer with Cross Entropy Loss, evaluating performance metrics such as accuracy.

- **Evaluation:** Evaluated the model on a separate test set to measure its accuracy and visualize predictions.

---

## Installation

To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/cat-vs-dog-classifier.git
   cd cat-vs-dog-classifier
   ```

---


## Folder Structure

```
cat-vs-dog-classifier/
├── classifier_pytorch.ipynb  # The implementation of the model and dataset
├── README.md                 # Project overview and documentation (you're here!)
└── data/
    ├── train/                # Training data directory
    ├── test/                 # Testing data directory
    └── validation/           # Validation data directory
```

---

## Training and Evaluation

- **Data Preprocessing:** Images are resized, cropped, and normalized using torchvision transforms.

- **Model Architecture:** The CNN consists of several convolutional layers followed by fully connected layers for classification.

- **Training:** Utilizes PyTorch's DataLoader for batch processing and GPU acceleration.

- **Evaluation:** Metrics such as accuracy, loss, and confusion matrix are computed during evaluation.

---

## Results

The trained model achieves an accuracy of 74% on the test set, demonstrating its effectiveness in classifying cats and dogs from images.

---

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you want to change.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
