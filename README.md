
# N-gram Language Model

This Python script implements an N-gram language model using tokenized text. It provides utilities for processing text, generating N-gram statistics, and calculating probabilities with various smoothing techniques like Laplace and Maximum Likelihood Estimation (MLE).

### Key Functions:
- generate_ngram_statistics(tokens, n): Calculates N-gram and context frequencies.
- process_text(input_text, word_stats): Tokenizes and cleans the input text.
- create_vocabulary(corpus, min_frequency): Creates a vocabulary from the corpus, applying a minimum frequency threshold.
- calculate_probability(ngram, ngram_frequencies): Calculates N-gram probabilities with different smoothing methods.
- evaluate_perplexity(data, ngram_frequencies): Evaluates model performance using perplexity.

### Usage:
1. Prepare your text corpus.
2. Call the functions to preprocess the text, create vocabulary, and generate N-gram statistics.
3. Evaluate model performance using perplexity scores for different N-gram models.

### Running the Script:
Run the script as the main program to perform N-gram analysis on the provided dataset.


python main.py


