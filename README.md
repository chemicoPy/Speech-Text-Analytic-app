
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

![GitHub contributors](https://img.shields.io/github/contributors/chemicopy/Speech-Text-Analytic-app)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed-raw/judeleonard/SpeechText-Analytic-App)
![GitHub repo size](https://img.shields.io/github/repo-size/chemicopy/Speech-Text-Analytic-app)
[![GitHub stars](https://img.shields.io/github/stars/chemicopy/Speech-Text-Analytic-app?color=orange&logo=github)](https://github.com/chemicopy/Speech-Text-Analytic-app/stargazers)

# Project Overview
This is an AI web application that offers transcription of text to speech and speech to text using Google pretrained model. The goal is to extract insight from audio speech in the form of text

[Live App](https://chemicopy-speech-text-analytic--speech-text-analytic-app-gx6xu8.streamlitapp.com/)

## App Demo

![app demo](https://user-images.githubusercontent.com/66210738/176871820-b81f7b50-1a65-4a6e-bc00-0ae721670d1e.gif)

## Inspiration
The most common part of the Natural Language Processing is the written text, which is hugely available and can come in the form of documents, scraped data from websites etc. Many firms and organization rely on the processing of 
these collected data to derive insights to better serve their customers. On the other hand, speech is another basic form of human language that is quite difficult to process and achieve state of the art performance owing to it's dependency on several factors. There are many organization for instance, the Telecommunication industries that generate audio files
from their customers in the form of complaints or expression regarding a particular product or service. The major goal of this project is to leverage google API to transform audio speech to text and apply the same processing steps like every other text document to
extract insights like specific key words from the speech and analyzing sentiment in the speech.
Another part of this project featured using Google translate to recognize the three major Nigerian native languages. However, google does not support this feature yet, but recognizes Nigerian accent which was included in the app.

## Further Improvement
- Developing a hate speech detecting algorithm to classify hate speech
- Training Neural Network model to classify raw audio files into __Sad__, __Happy__, __Disgust__, and __Fearful__
