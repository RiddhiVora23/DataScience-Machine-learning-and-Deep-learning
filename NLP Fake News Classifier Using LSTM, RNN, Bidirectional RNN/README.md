# NLP Fake News Classifier Using LSTM, RNN, Bidirectional RNN

## Introduction

The "Fake News Classifier Using LSTM, RNN, Bidirectional RNN" project aims to tackle the challenge of fake news detection using advanced natural language processing and deep learning techniques. Leveraging Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM) networks, and Bidirectional LSTMs, this project builds and evaluates models to distinguish between real and fake news articles.

## Dataset

The dataset used for this project can be found [here](https://www.kaggle.com/c/fake-news/data#).

## Workflow

### Data Collection

- Gather labeled news articles from the dataset for training and testing.

### Data Preprocessing

- **Text Cleaning:** Remove non-alphabetic characters.
- **Normalization:** Convert text to lowercase.
- **Stopword Removal:** Eliminate common stopwords.
- **Stemming:** Reduce words to their root forms.
- **One-Hot Encoding:** Convert text into numerical format.

### Model Building

- Implement and configure RNN, LSTM, and Bidirectional LSTM models.
- Optimize hyperparameters for each model.

### Model Training

- Train models on preprocessed data.
- Monitor metrics like loss and accuracy.

### Model Evaluation

- Evaluate models on a test dataset.
- Compute metrics such as accuracy, precision, recall, and F1-score.

### Ethical Considerations

- Address data bias, transparency, and privacy concerns.

### Visualization

- Visualize training and validation performance metrics.

### Conclusion and Recommendations

- Summarize model performance and suggest further improvements.

## Model Details

- **RNN Model:** Achieved around 91% validation accuracy, but showed signs of overfitting.
- **LSTM Model:** Also achieved approximately 91% accuracy with similar overfitting concerns.
- **Bidirectional LSTM Model:** Demonstrated around 90% accuracy, capturing context from both past and future.

## References

- [Understanding RNN and LSTM](https://medium.com/analytics-vidhya/undestanding-recurrent-neural-network-rnn-and-long-short-term-memory-lstm-30bc1221e80d)
- [Bi-directional RNN Basics](https://medium.com/analytics-vidhya/bi-directional-rnn-basics-of-lstm-and-gru-e114aa4779bb)
- [RNN Overview](https://medium.com/@humble_bee/rnn-recurrent-neural-networks-lstm-842ba7205bbf)
- [In-Depth Tutorial on RNN and LSTM](https://medium.com/analytics-vidhya/in-depth-tutorial-of-recurrent-neural-network-rnn-and-long-short-term-memory-lstm-networks-3a782712a09f)

