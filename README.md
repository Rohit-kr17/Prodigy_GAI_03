# Markov Chain Text Generator

This project demonstrates a simple text generation algorithm using Markov Chains. The script processes input text, builds a Markov Chain model, and generates new text based on that model.

## Overview

The code performs the following steps:

1. **Data Preparation**: Converts input text to lowercase and splits it into individual words.
2. **Model Building**: Constructs a Markov Chain model from the processed words. The model predicts the next word based on the previous `n` words.
3. **Text Generation**: Generates a sequence of words using the Markov Chain model. The length of the generated text and the seed for the generation can be specified.

## Requirements

- Python 3.x

## Usage

1. **Prepare Your Data**: Provide a string of text that you want to use for training the Markov Chain model.
2. **Build the Markov Chain Model**: The model is built by specifying the number of preceding words (`n`) to consider for predicting the next word.
3. **Generate Text**: Specify the length of the text to be generated and optionally provide a seed phrase to start the text generation.

## Example

Here’s an example of how to use the code:

1. **Preprocess the Input Text**: Convert the text into a list of words.
2. **Build the Markov Chain**: Create a Markov Chain model with `n=2` (bigrams).
3. **Generate Text**: Produce a 20-word sequence starting with the seed phrase `"this is"`.

## Notes

- The quality of generated text may vary based on the input text and the value of `n`.
- Ensure that the input text is sufficiently large for meaningful results.

## License

This project is provided for educational purposes. You are free to use and modify it as needed.

## Author

Rohit Kumar
