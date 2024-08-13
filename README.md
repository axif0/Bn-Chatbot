

# Chatbot using Seq2Seq LSTM Models

This repository contains code for building a Chatbot using Seq2Seq LSTM models in Keras.

## Introduction

In this project, we leverage the power of Seq2Seq LSTM models to create a functional Chatbot capable of answering user questions. This approach can be applied to various domains, such as e-commerce or educational websites.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- TensorFlow
- Keras
- bnlp_toolkit
- stopwordsiso
- wikipedia

Install them using the following command:

```bash
pip install -r requirements.txt
```

### Data Preparation

Download the [chatterbot/english dataset](https://www.kaggle.com/kausr25/chatterbotenglish) and extract it into the `data` directory.

```bash
# Example download command
wget https://github.com/shubham0204/Dataset_Archives/blob/master/chatbot_nlp.zip?raw=true -O chatbot_nlp.zip
unzip chatbot_nlp.zip
```

## Training the Model

Run the Jupyter notebook `ChatBot_With_Seq2Seq.ipynb` to train the Seq2Seq LSTM model. The model will be saved as `model.h5`.

```bash
jupyter notebook ChatBot_With_Seq2Seq.ipynb
```

## Inference and Chatting with the Chatbot

After training, you can interact with the Chatbot by running the provided inference code. Enter a question, and the Chatbot will generate an appropriate response.

```bash
python chatbot_inference.py
```

## Additional Notes

- The `chatbot_inference.py` script allows interactive chatting with the trained Chatbot.
- The `bengalianalyzer` library is used for Bangla text analysis in certain parts of the code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to adjust and modify the content based on your specific project details and preferences.
