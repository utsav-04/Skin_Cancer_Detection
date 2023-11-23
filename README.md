# Skin Cancer Classification Project

## Overview

This project aims to classify skin cancer images into different categories using deep learning. It involves data augmentation, model training, and evaluation. I had used three techniques to improve model accuracy.
1. I had use basic CNN model in order to get accuracy. But after model fitting I observe overfitting model, as there was a huge difference between accuracy and val_accuracy.
2. Now i use data augmentation in order to improve accuracy and remove overfitting problem. now i find that the difference between accuracy and val_accuracy has came down but still a huge scope of improvement is there in term of accuracy value.
3. The major problem that was caught is data imbalance as in datsaet i have 9 types of skin cancer image but each folder have very much different number of image present. So I used python Augmentor library in order to generate equal amount of image in each folder . then I used my CNN model and finally i got 92 % acccuracy which was far better than 82% (overfitting) and 50% .

## Dataset

The dataset used in this project is obtained from the International Skin Imaging Collaboration (ISIC). It consists of images categorized into different types of skin lesions.

### Requirements

- Python 3.x
- TensorFlow
- Keras
- Augmentor
- NumPy
- Matplotlib

### Installation

1. Clone the repository:

    ```bash
    git clone "use https link here"
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.


