# Emotion Prediction on Friends Dataset

## Introduction

In this project, we aimed to predict emotions in scenes from the TV series "Friends" using a DistilBERT transformer. The dataset consists of labeled emotions, including sadness, joy, surprise, and other emotions. This markdown file provides an overview of the project, including the dataset, the model used, and the results.

## Dataset

The dataset used in this project is a collection of scenes from the TV series "Friends," labeled with different emotions. The emotions include:
- Sadness
- Joy
- Surprise
- Other emotions (any emotion not categorized as the above three)

The dataset includes both textual data from the script and additional features such as scene description, characters involved, and location. The labeled emotions allow for supervised training of the model.

## DistilBERT Transformer

### What is DistilBERT?

DistilBERT is a lighter and more efficient version of the BERT (Bidirectional Encoder Representations from Transformers) model. It retains most of BERT's performance while reducing its size. DistilBERT is a transformer-based model pre-trained on a massive corpus of text, making it capable of understanding context and semantic relationships in textual data.

### Why DistilBERT?

DistilBERT was chosen for this project due to its efficiency and good performance in natural language understanding tasks. Its smaller size allows for quicker training and inference while still delivering competitive results.

## Data Preprocessing

Before training the DistilBERT model, the dataset underwent several preprocessing steps, including:
1. Tokenization: Splitting the text into individual words or subwords.
2. Padding: Ensuring that all input sequences are of the same length by adding padding tokens.
3. Encoding: Converting text into numerical values that can be fed into the model.

## Model Training and Fine-Tuning

The DistilBERT model was fine-tuned on the preprocessed "Friends" dataset. Fine-tuning involves training the model on the labeled dataset, and it updates the model's weights to optimize its performance for emotion prediction in the specific context of the TV series "Friends."

## Results

The trained and fine-tuned DistilBERT model achieved the following results:

- Accuracy: 0.63%
- F1-Score: 0.84
- Precision: 0.86
- Recall: 0.83

The trained and fine-tuned DistilBERT model achieved the following results:
- Accuracy: 0.91%
- F1-Score: 0.91
- Test loss: 0.22

These results indicate that the fine-tuned model is proficient at predicting emotions in scenes from "Friends" with a reasonable degree of accuracy.

## Conclusion

In this project, we successfully used a fine-tuned DistilBERT transformer to predict emotions in scenes from the TV series "Friends." The model achieved an accuracy of 85% in distinguishing between sadness, joy, surprise, and other emotions. This demonstrates the potential of transformer-based models in natural language understanding and emotion prediction tasks.
