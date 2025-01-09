# sentiment-classification-project
Fine-tuned DistilBERT for Sentiment Classification using Hugging Face Transformers
# Sentiment Classification Project

This project demonstrates how to fine-tune **DistilBERT**, a pre-trained transformer model, to classify text as either positive or negative sentiment. It is designed to work efficiently on devices with limited computational resources.

---

## Project Overview

The main goal of this project is to predict whether a given sentence expresses a positive or negative sentiment. For example:
- **Input**: "I love this movie!"
- **Output**: Positive sentiment

By following this project, you can learn the basics of fine-tuning pre-trained models for text classification tasks.

---

## Steps in the Project

1. **Dataset Preparation**:
   - Used a CSV file containing sentences and their sentiment labels.
   - Example:
     ```csv
     text,label
     I love this movie,1
     This film was terrible,0
     ```

2. **Tokenization**:
   - Used Hugging Face’s tokenizer to preprocess the text into a format suitable for DistilBERT.

3. **Model Fine-Tuning**:
   - Fine-tuned the `distilbert-base-uncased` model for sentiment classification.
   - Trained on a small dataset to demonstrate the workflow.

4. **Evaluation**:
   - Evaluated the model's performance using metrics like accuracy, precision, recall, and F1 score.

5. **Saving and Inference**:
   - Saved the fine-tuned model locally for future predictions.
   - Example: "This is amazing!" → Predicted as **Positive**.

