pandas, numpy: Used for data manipulation.

Tokenizer, pad_sequences: Tools for converting text to numerical sequences and ensuring all sequences are the same length.

Sequential, Embedding, SimpleRNN, Dense: Components for building a neural network.

train_test_split: To split the data into training and test sets.

LabelEncoder: Converts categorical labels to numeric values.

Loads a CSV file containing the text data and labels.

Prints the first few rows to understand the structure.

Converts textual class labels into numeric values for model compatibility.

max_words: Only the most common 10,000 words will be kept.

max_len: All sequences will be padded/truncated to 100 tokens.

oov_token: Special token for out-of-vocabulary words.

Fits the tokenizer on the text data and converts it to sequences of integers.

Pads sequences to ensure uniform length (padding='post' adds zeros at the end).

Splits the dataset into training (80%) and testing (20%) sets.

Embedding: Converts word indices to dense vectors.

SimpleRNN: Recurrent layer with 64 units.

Dense(32, activation='relu'): Fully connected layer for feature learning.

Dense(..., activation='softmax'): Output layer for multi-class classification.

