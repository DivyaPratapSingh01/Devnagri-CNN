# Devanagari Character Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify handwritten Hindi characters from the Devanagari dataset.

## Dataset
[Devanagari Handwritten Character Dataset on Kaggle](https://www.kaggle.com/datasets/berlinsweird/devanagari)

- 46 classes of characters
- Images in grayscale
- Organized into train/test folders by class

## How to Use

1. Clone the repository or unzip the files.
2. Download and extract the dataset into a folder named `dataset/`
3. Run the `Devanagari_Character_Classification.ipynb` notebook.

## Model
- Input: 32x32 grayscale images
- 2 Conv2D + MaxPooling layers
- Dense + Dropout layer
- Softmax output layer

## Results
- Achieves over 90% test accuracy after 10 epochs (may vary)

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

## Author
Divya Pratap Singh
