# Fashion-MNIST Data Exploration

This project focuses on exploring and understanding the **Fashion-MNIST dataset** using Python and Jupyter Notebook.

The main objective is to load, inspect, and visualize clothing images as a first step toward building a machine learning classification model.

## Dataset

Fashion-MNIST is a dataset developed by Zalando Research, containing 70,000 grayscale images of clothing items divided into 10 categories.

- **Training set:** 60,000 images
- **Test set:** 10,000 images
- **Image dimensions:** 28 × 28 pixels
- **Number of classes:** 10

The clothing categories are:

T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, and Ankle boot.

Dataset source: [Fashion-MNIST — Zalando Research](https://github.com/zalandoresearch/fashion-mnist)

## Technologies Used

- **Python** — Data processing and analysis
- **NumPy** — Image data manipulation
- **pandas** — Data exploration and inspection
- **Matplotlib** — Image visualization
- **Jupyter Notebook** — Interactive development

## Project Overview

The notebook covers the following steps:

1. **Dataset loading:** Download and load Fashion-MNIST images and labels from IDX files.
2. **Data exploration:** Examine dataset dimensions, labels, and pixel values.
3. **Data transformation:** Convert images into flattened arrays containing 784 pixel features.
4. **Data visualization:** Display individual clothing images and a grid of labeled examples.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/firdawss-Elhaddouchi/fashion-mnist-classification.git
cd fashion-mnist-classification
```

Install the required libraries:

```bash
pip install notebook numpy pandas matplotlib
```

Launch Jupyter Notebook:

```bash
jupyter notebook notebook_class.ipynb
```

Run the notebook cells in order to explore the dataset and visualize the results.

The dataset files are downloaded automatically if they are not already available in `data/fashion/`.

## Results

The data exploration confirms:

- 60,000 training images with dimensions of 28 × 28 pixels.
- 784 pixel features per flattened image.
- 10 different clothing categories.
- Successful visualization of labeled clothing images.

## Future Improvements

- Train machine learning models for clothing classification.
- Evaluate model performance using accuracy and classification metrics.
- Visualize predictions and analyze classification errors.

## Project Structure

```text
fashion-mnist-classification/
├── notebook_class.ipynb
└── data/
    └── fashion/
```

## Reference

[Zalando Research — Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)
