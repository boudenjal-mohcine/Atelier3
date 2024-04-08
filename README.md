# Lab Report: Introduction to PyTorch and Sequence Models

This lab aims to provide an introduction to PyTorch and build deep neural network architectures for natural language processing using sequence models. The lab consists of two parts: 

## Part 1: Classification Task
In this part, we collected text data from several Arabic websites focusing on the topic of "Alhijra" using web scraping libraries like BeautifulSoup. We then prepared the dataset as follows:

| Text (Arabic Language) | Score |
|------------------------|-------|
| Text 1                 | 6     |
| Text 2                 | 7.5   |

The score represents the relevance of each text, ranging from 0 to 10.

### Preprocessing Pipeline
We established an NLP preprocessing pipeline including tokenization, stemming, lemmatization, stop words removal, and discretization.

### Model Training and Evaluation
We trained four different models using RNN, Bidirectional RNN, GRU, and LSTM architectures. After training and tuning hyperparameters, we evaluated the models using standard metrics and calculated the BLEU score.

### Results

| Model               | Test Loss | Test MAE |
|---------------------|-----------|----------|
| RNN                 | 9.89      | 2.84     |
| Bidirectional RNN   | 9.36      | 2.75     |
| GRU                 | 11.22     | 3.01     |
| LSTM                | 9.81      | 2.83     |

## Part 2: Transformer (Text Generation)
In this part, we installed the pytorch-transformers library and fine-tuned the pre-trained GPT2 model using a custom dataset. We generated new paragraphs based on given sentences.

### Dataset
We used jokes as our dataset for fine-tuning the GPT2 model.

### Conclusion
In conclusion, this lab provided hands-on experience with PyTorch and sequence models for natural language processing tasks. We learned how to preprocess text data, train different architectures, evaluate model performance, fine-tune pre-trained models, and generate text.

This lab report was prepared by Mohcine Boudenjal under the guidance of Pr. Lotfi ELAACHAK.
