# Spam Detection Project

## Overview
This project aims to tackle the prevalent issue of spam detection through various machine learning algorithms, exploring the effectiveness of simple perceptrons, artificial neural networks (ANN), recurrent neural networks (RNN), long short-term memory networks (LSTM), and bidirectional LSTM (Bi-LSTM). Leveraging a comprehensive spam and ham dataset, the project demonstrates how each algorithm can be applied to filter out unwanted messages, providing a detailed comparison of their performance.

## Dataset
The project uses the `spam_ham_dataset.csv`, which includes a mix of spam and non-spam (ham) messages. This dataset serves as the foundation for training and testing our models, allowing us to evaluate their effectiveness in real-world spam detection scenarios.

## Models Overview
- **Simple Perceptron Spam Filter**: Utilizes a straightforward perceptron model to classify messages, serving as a baseline for comparison with more complex models.
- **ANN for Spam Detection**: Implements an artificial neural network to capture non-linear relationships in the data, enhancing the detection capabilities beyond the simple perceptron.
- **RNN Spam Detection**: Applies recurrent neural network architecture to exploit the sequential nature of text data, aiming to improve context understanding.
- **LSTMs for Spam Detection**: Employs long short-term memory units to address the limitations of traditional RNNs, particularly in handling long-term dependencies.
- **Bi-LSTM**: Incorporates a bidirectional LSTM approach to further refine the model's ability to capture context from both past and future input sequences for more accurate spam detection.

## Getting Started
To get started with this project, clone the repository and install the required dependencies listed in `requirements.txt`. Ensure you have Python 3.6 or newer installed.

## Usage
Each Jupyter notebook in the repository corresponds to a different model. To test a model, simply open its notebook and follow the instructions within. You can train the models using the provided dataset and evaluate their performance through the metrics displayed at the end of each notebook.

## Results
The project includes a comparative analysis of each model's accuracy, precision, recall, and F1 score. These metrics provide insights into the models' effectiveness at detecting spam messages, helping identify the most promising approaches for real-world applications.

## Contributing
Contributions to this project are welcome. In the future refer to the `CONTRIBUTING.md` file for guidelines on how to make contributions.
