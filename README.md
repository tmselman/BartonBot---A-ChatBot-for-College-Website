# Chatbot Deployment with Flask and JavaScript

This Chatbot was created with Flask and Jscript.
 The chatbot works with Flask prediction API. The used html and javascript files can run completely separate from the Flask App then.

Install dependencies ;

$ (venv) pip install Flask torch torchvision nltk

Install nltk package ;

$ (venv) python
>>> import nltk
>>> nltk.download('punkt')

The intents.json file contains the intents and responses for this chatbot.

Run ;

$ (venv) python train.py
