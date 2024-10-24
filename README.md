# Brain Tumor Detection using MobileNet and Transfer Learning

## Overview
This project uses a pre-trained MobileNet model with transfer learning for brain tumor detection. The model is trained on grayscale images of size 512x512 and aims to classify images into four classes: glioma, meningioma, no tumor, and pituitary. The training process involves image preprocessing, data augmentation, and fine-tuning.


## Evaluation
The model's performance is evaluated using the test dataset, and accuracy is reported. Additionally, the training history is visualized for both accuracy and loss.

## Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Future Improvements
-After training the model, I discovered that the model gave inaccurate predicitions therefore making this project still a work in progress. I will update it as soon as I find a solution

## Acknowledgments
Special thanks to the creators of the dataset (https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) and the developers of the pre-trained MobileNet model.
