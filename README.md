# The Empathy Engine – Emotion-Aware Text-to-Speech Service

## Project Description

The Empathy Engine is a Python-based Text-to-Speech (TTS) application that converts user-provided text into speech while dynamically adjusting vocal behavior based on the detected sentiment of the text.

The application analyzes the input text, classifies it into one of three emotional categories (Positive, Neutral, or Negative), and then modifies voice-related parameters such as speaking rate and volume before generating the speech output.

This project is designed as a proof-of-concept for creating more expressive and human-like AI voice interactions instead of standard monotonic text-to-speech systems.

---

## Core Features

- Accepts text input from the user through the command line
- Performs sentiment analysis on the input text
- Classifies text into three emotion categories:
  - Positive / Happy
  - Neutral
  - Negative / Frustrated
- Modulates at least two voice parameters:
  - Speaking Rate
  - Volume
- Generates spoken output using a TTS engine
- Simple and easy-to-run local Python project

---

## Technologies Used

- Python 3
- pyttsx3
- TextBlob
- NLTK

---

## Project Structure

```bash
text-to-speech-sentiment-analysis/
│── app.py
│── README.md
│── LICENSE
│── .gitignore