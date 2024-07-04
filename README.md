
# Text Generation Using LSTM Neural Network

This repository contains a Python project for generating text using an LSTM (Long Short-Term Memory) neural network. The model is trained on a text corpus, learning to predict and generate sequences of characters based on input sequences. This project demonstrates skills in neural network design, text preprocessing, and sequence modeling.

## Features

- **Data Loading and Preprocessing**:
  - Load and preprocess a text corpus.
  - Convert text to lowercase for uniformity.
  - Create character-to-integer mappings.
  - Prepare datasets of input-output pairs encoded as integers.

- **Model Design**:
  - Build a Sequential model with an LSTM layer using Keras.
  - Define a Dense output layer with softmax activation for character prediction.

- **Training**:
  - Compile the model with categorical cross-entropy loss and the Adam optimizer.
  - Train the model on the prepared dataset to minimize prediction error.

- **Text Generation**:
  - Generate text by seeding the model with an initial sequence.
  - Predict subsequent characters iteratively to generate coherent text sequences.

## Tools and Technologies

- **Python**: Core programming language used for the project.
- **TensorFlow/Keras**: Used for building and training the LSTM model.
- **NumPy**: For numerical operations and data manipulation.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-generation-lstm.git
   cd text-generation-lstm
   ```

2. Install required libraries:
   ```bash
   pip install tensorflow numpy
   ```

3. Place the text file (`145-0.txt`) in the appropriate directory.

4. Run the Jupyter notebook to execute the code and generate text:
   ```bash
   jupyter notebook text_genrate.ipynb
   ```

## Results

- The model generates text sequences based on learned patterns from the training corpus.
- Demonstrates the capability of LSTM networks to model and generate sequential data.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

