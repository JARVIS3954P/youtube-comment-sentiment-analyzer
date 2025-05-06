# YouTube Comments Sentiment Analysis with BiLSTM

This project implements a **Bidirectional LSTM (BiLSTM)** neural network to classify YouTube comments into three sentiment categories: **negative (0), neutral (1), and positive (2)**. 

### Key Features:
- **Data Processing**: Handles class imbalance with oversampling and class weighting
- **Model Architecture**: Uses BiLSTM layers with dropout and batch normalization for robust performance
- **Training**: Implements early stopping, learning rate reduction, and model checkpointing
- **Evaluation**: Achieves 72% accuracy with strong performance on positive sentiment detection

### Usage:
1. Load pre-trained model and tokenizer
2. Preprocess new comments with the same tokenization
3. Predict sentiment scores

### Results:
- Precision/Recall: Positive (0.86/0.82), Neutral (0.56/0.61), Negative (0.46/0.49)
- Visualized with confusion matrix and learning curves

The model is ready for deployment in applications requiring automated sentiment analysis of user comments.
