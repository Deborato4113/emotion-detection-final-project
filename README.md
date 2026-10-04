# Emotion Detector

## Project Overview

The **Emotion Detector** is a Python-based web application that uses the **Watson NLP library** to analyze a user's text and identify the emotions expressed in it.

The application detects five different emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

It also determines the **dominant emotion** expressed in the provided text.

## Technologies Used

- Python
- Flask
- Watson NLP
- Requests
- HTML
- CSS
- JavaScript
- unittest
- Pylint

## Project Structure

```text
EmotionDetection/
├── __init__.py
└── emotion_detection.py

templates/
└── index.html

server.py
test_emotion_detection.py
requirements.txt
README.md
```

## Features

- Detects emotions from natural-language text
- Identifies the dominant emotion
- Provides a web interface using Flask
- Handles invalid or blank input
- Includes automated unit tests
- Supports Python package-style imports
- Includes static code analysis using Pylint

## How to Run

Install the required dependencies:

```bash
pip3 install -r requirements.txt
```

Run the Flask application:

```bash
python3 server.py
```

Then open the application in a web browser using the URL provided by the development environment.

## Testing

Run the unit tests using:

```bash
python3 -m unittest test_emotion_detection.py
```

## Static Code Analysis

Run Pylint using:

```bash
pylint server.py
```

## Project Objective

The objective of this project is to demonstrate how an AI-based emotion detection service can be integrated into a Python web application using Watson NLP and Flask.
