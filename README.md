
# Shakespearean Text Generation with RNN

This Jupyter notebook demonstrates how to train a Recurrent Neural Network (RNN) to generate text in the style of William Shakespeare. The model is trained on a corpus of Shakespeare’s works, and it learns to generate text character by character.

## Project Overview

- **Objective**: Train an RNN model to generate text similar to Shakespeare's writing.
- **Dataset**: The notebook uses a dataset containing the complete works of William Shakespeare, which is downloaded from a public source.
- **Model**: A simple RNN model is built using TensorFlow and Keras.

## Steps in the Notebook

1. **Imports**: Necessary libraries such as TensorFlow, Keras, and others are imported.
2. **Data Loading**: The Shakespeare text dataset is downloaded and loaded into memory.
3. **Data Preprocessing**: The text is processed into a format suitable for training the RNN model. This includes creating a vocabulary of unique characters and converting the text into sequences of character IDs.
4. **Model Definition**: An RNN model is defined, utilizing layers like `Embedding`, `SimpleRNN`, and `Dense`.
5. **Training**: The model is trained on the prepared dataset.
6. **Text Generation**: After training, the model is used to generate new text that mimics Shakespeare's style.

## Usage

To run the notebook, you need to have Python installed along with the required packages. The main dependencies are listed below:

- TensorFlow
- NumPy

You can install the required packages using:

```bash
pip install tensorflow numpy
```

Run the notebook using Jupyter:

```bash
jupyter notebook Text_generation.ipynb
```

## Results

After training, the model will be able to generate text in the style of Shakespeare. The output can vary depending on the length of training and model complexity.
