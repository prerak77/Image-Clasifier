# Image Classifier - CIRFA-10

**Welcome to the CIRFA-10 Image Classifier GitHub Repository!**

This project offers a robust image classifier capable of recognizing 10 distinct classes from the CIRFA-10 dataset with an impressive accuracy of 80%. Developed using the PyTorch deep learning framework, the classifier leverages NumPy and Matplotlib for efficient data manipulation and visualization.

## About the CIRFA-10 Dataset

The CIRFA-10 dataset comprises 60,000 32x32 pixel color images categorized into 10 classes, each containing 6,000 images. The classes include airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The classifier underwent training on a subset of 50,000 images and was evaluated on the remaining 10,000 images.

## Usage

1. **Predicting Image Class:**
   Run the `main.py` script with the path to your image as an argument, and the script will output the predicted class for that image.

   ```bash
   python main.py /path/to/your/image.jpg
   ```

## Project Structure

- **main.py:** Script for predicting the class of a given image.
- **/data:** Directory for storing the CIRFA-10 dataset.

