# NLP

**What is Sentiment Analysis?**
Sentiment analysis is a natural language processing technique that identifies the polarity of a given text. There are different flavors of sentiment analysis, but one of the most widely used techniques labels data into positive, negative and neutral.

Using pre-trained models publicly available on the Hub is a great way to get started right away with sentiment analysis. These models use deep learning architectures such as transformers that achieve state-of-the-art performance on sentiment analysis and other machine learning tasks. However, you can fine-tune a model with your own data to further improve the sentiment analysis results and get an extra boost of accuracy in your particular use case.

The IMDB dataset contains 25,000 movie reviews labeled by sentiment for training a model and 25,000 movie reviews for testing it. But we have considered only 5000 movie reviews and divided it into train and test dataset.

**BERT - Bidirectional Encoder Representations from Transformers**

BERT, which stands for "Bidirectional Encoder Representations from Transformers," is a state-of-the-art natural language processing (NLP) model developed by Google AI. It was introduced in a research paper titled "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding," published in 2018.

BERT is a type of transformer model, which is a deep neural network architecture designed for various NLP tasks. What makes BERT unique and powerful is its bidirectional pre-training. Unlike previous language models that processed text in a left-to-right or right-to-left manner, BERT is trained on a masked language modeling task where it learns to predict missing words in sentences by considering the context from both directions. This allows BERT to capture richer contextual information and achieve a deeper understanding of language.

BERT pre-training involves training the model on a massive corpus of text, such as Wikipedia articles and books. Once pre-trained, BERT can be fine-tuned on specific NLP tasks, such as text classification, named entity recognition, sentiment analysis, question answering, and more. Fine-tuning involves training the model on task-specific labeled data to adapt its learned representations to the particular task.
