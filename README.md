## NancyBot – Chatbot using PyTorch

A simple AI chatbot built with PyTorch and NLTK.

Easy-to-understand implementation for beginners learning NLP and neural networks.

Uses a Feed Forward Neural Network with two hidden layers for intent classification.

Fully customizable — just edit intents.json with your own patterns and responses, then retrain the model.

## Installation
### Create an environment

You can use either conda or venv
```console
mkdir chatbot
cd chatbot
python -m venv venv
```
### Activate it

Windows:
```console
venv\Scripts\activate
```

Mac/Linux:
```console
source venv/bin/activate
```
### Install Dependencies
```console
pip install torch nltk

```
If NLTK gives an error, download this once:
```console
python
>>> import nltk
>>> nltk.download('punkt')
>>> exit()
```
## Training the Model

Run this command to train your chatbot:
```console
python train.py

```
This will save a trained model as data.pth.

## Start Chatting

After training, chat with your bot:
```console
python chat.py
```
## Customize for Your Own Use

Edit intents.json to add your own tags, patterns, and responses.
Example:
```console
{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["hi", "hello", "hey"],
      "responses": ["Hello!", "Hey there!", "Hi! How can I help you?"]
    }
  ]
}
```

Then retrain using python train.py.

## About Me

👩‍💻 Nancy Rose C
B.Tech Artificial Intelligence and Data Science
Aspiring AI Engineer | Loves exploring NLP & Deep Learning
