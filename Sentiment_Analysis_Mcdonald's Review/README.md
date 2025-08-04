# CNN-Based Sentiment Classification on McDonald's Reviews

This project builds a Convolutional Neural Network (CNN) to classify customer reviews of McDonald's into three sentiment categories: **positive**, **neutral**, and **negative**.

## Dataset
- Source: [McDonald's Store Reviews on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/mcdonalds-store-reviews/data)
- Sentiment mapping:
  - **Positive**: 4–5 stars
  - **Neutral**: 3 stars
  - **Negative**: 1–2 stars

## Model
- Pre-trained **GloVe** embeddings (100d)
- Two Conv1D layers with BatchNorm, Dropout, and L2 regularization
- Global Max Pooling and Dense layers
- Softmax output for multiclass classification

## Results
- **Test accuracy**: 75%
- **High performance** on positive and negative classes
- **Lower precision** on neutral class due to semantic overlap

## Tools & Libraries
- Python, TensorFlow/Keras
- NLTK, scikit-learn, Matplotlib, Seaborn

## Files
- `cnn_sentiment_classification.ipynb`: Full model notebook
- `glove.6B.100d.txt`: Pre-trained word embeddings (downloaded separately)
