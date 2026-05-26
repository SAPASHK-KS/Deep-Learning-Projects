# WhatsApp Chat Sentiment Analyzer using LSTM

## Overview

This project is a Deep Learning based WhatsApp Chat Sentiment Analyzer developed using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM).

The model classifies chat messages into three sentiment categories:

- Positive
- Negative
- Neutral

The project demonstrates the complete Natural Language Processing (NLP) pipeline including text preprocessing, tokenization, sequence padding, label encoding, and sentiment prediction using LSTM.

---

## Features

- Sentiment classification of chat messages
- NLP preprocessing pipeline
- Tokenization and sequence padding
- LSTM-based deep learning model
- Multi-class sentiment prediction
- Real-time custom message prediction
- Clean and modular notebook implementation

---

## Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- Scikit-learn
- Regular Expressions (re)
- Jupyter Notebook / VS Code

---

## Deep Learning Concepts Covered

- Natural Language Processing (NLP)
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Text Tokenization
- Sequence Padding
- Embedding Layer
- Multi-class Classification

---

## Dataset Structure

The dataset contains two columns:

| Column | Description |
|--------|-------------|
| message | Chat message text |
| sentiment | Sentiment label (positive, negative, neutral) |

### Example Dataset

```csv
message,sentiment
"Semma movie da",positive
"Worst day ever",negative
"Okay send notes",neutral
```

---

## Project Workflow

```text
Dataset
   ↓
Text Cleaning
   ↓
Tokenization
   ↓
Sequence Padding
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
Embedding Layer
   ↓
LSTM Model
   ↓
Sentiment Prediction
```

---

## Model Architecture

```python
model = Sequential()

model.add(Embedding(input_dim=5000, output_dim=128, input_length=20))

model.add(LSTM(128))

model.add(Dense(3, activation='softmax'))
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/whatsapp-chat-sentiment-analyzer.git
```

Move into the project directory:

```bash
cd whatsapp-chat-sentiment-analyzer
```

Install required dependencies:

```bash
pip install pandas tensorflow scikit-learn
```

---

## Running the Project

Open the notebook:

```bash
whatsapp_sentiment.ipynb
```

Run all cells step-by-step inside VS Code or Jupyter Notebook.

---

## Sample Prediction

### Input

```text
"Semma movie da"
```

### Output

```text
Positive
```

---

## Applications

- WhatsApp chat analysis
- Social media sentiment analysis
- Customer feedback analysis
- Review classification
- Toxic message detection
- Opinion mining

---

## Future Enhancements

- Streamlit Web Application
- Emoji sentiment analysis
- Real-time WhatsApp chat integration
- Voice-based sentiment analysis
- Attention Mechanism with BiLSTM
- Advanced NLP preprocessing

---

## Project Structure

```text
WhatsappDL/
│
├── chat_dataset.csv
├── whatsapp_sentiment.ipynb
├── README.md
```

---

## Learning Outcomes

This project helped in understanding:

- Deep Learning fundamentals
- NLP preprocessing techniques
- Sequence learning using LSTM
- Sentiment classification
- TensorFlow/Keras implementation
- Real-world AI application development

---
