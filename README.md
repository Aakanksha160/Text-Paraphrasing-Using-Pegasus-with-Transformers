# Text-Paraphrasing-Using-Pegasus-with-Transformers
This project uses Google's Pegasus model for text paraphrasing with the Hugging Face Transformers library in Python. It allows users to generate diverse, contextually accurate paraphrases, with adjustable parameters like beam search, output quantity, and randomness, offering flexibility in controlling the quality of paraphrased results.

# Project Overview:
This project demonstrates how to use Google's Pegasus model for text paraphrasing using the Hugging Face transformers library in Python. Pegasus is a pre-trained model designed for abstractive summarization tasks and is highly effective for generating paraphrases of a given text. By leveraging the power of sequence-to-sequence modeling, this repository enables you to easily paraphrase sentences in a meaningful and contextually accurate way.

# Tools Used:
Python
Hugging Face Transformers Library
SentencePiece
Google’s Pegasus Pretrained Model

# Project Features:
Text Tokenization: Prepares the input text for model processing using the PegasusTokenizer.
Paraphrasing: Leverages the PegasusForConditionalGeneration model to generate multiple paraphrases of the given text.
Customizable Parameters: Users can control parameters like the number of returned paraphrases (num_return_sequences), search width (num_beams), and randomness (temperature).

# Installation
To get started with this project, make sure to install the necessary libraries:

```bash
pip install transformers
pip install SentencePiece
```

# Pretrained Model:
To use the pretrained Pegasus model for paraphrasing, you need to download the model and tokenizer files. You can download them from the following links:

1. Tokenizer File
2. Model File

# Results:
- The paraphrasing model successfully generates multiple paraphrases for a given input.
- The quality of paraphrases can be adjusted by tuning the num_beams (beam search) and num_return_sequences (number of paraphrases).
- Adjusting the temperature parameter controls the randomness of the generated paraphrases, where a higher value results in more diverse outputs.

  ![Screenshot 2024-12-02 155323](https://github.com/user-attachments/assets/4f0096c9-f7be-40f5-8134-ac4be1f37077)

  ![Screenshot 2024-12-02 155256](https://github.com/user-attachments/assets/b34931a5-8391-4d3c-a986-e7869fffbb53)

  ![Screenshot 2024-12-02 155323](https://github.com/user-attachments/assets/43a11ddd-2b65-422a-860f-6187d82e3cda)


  

