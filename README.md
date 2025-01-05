# MNIST Digit Classification

## **Overview**
This project focuses on building a machine learning model to classify handwritten digits from the MNIST dataset, a benchmark dataset widely used in the field of computer vision and deep learning. The goal of the project is to implement and train an Artificial Neural Network (ANN) to accurately predict digits (0–9) based on their pixel values.

## **Dataset**
The dataset is loaded directly using the **keras.datasets.mnist.load_data()** function, which provides easy access to the dataset as part of TensorFlow/Keras libraries.

## Key Features of Dataset:
1. **Input Features:** Each image consists of 784 features, representing pixel values of a flattened 28x28 grayscale image.

2. **Pixel Intensity Range:** Pixel values range from 0 to 255, indicating the brightness of each pixel. These values can be normalized to the range [0, 1] for improved model performance.

3. **Data Split:** Training Set: 60,000 samples. Test Set: 10,000 samples

## **Techstack**
1. Programming Language - Python
2. Libraries - numpy, pandas, matplotlob, seaborn, sklearn, keras, tensorflow
3. Version Control - Git, GitHub, VSCode

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shreyas19-ai/MNIST-Digit-Classification.git
2. **Create a virtual environment (optional but recommended):** 
   ```bash
   python -m venv myenv  
   myenv/Scripts/activate 
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
