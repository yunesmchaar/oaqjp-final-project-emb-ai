 
# Emotion Detection Application

![IBM Skills Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-PY0224EN-Coursera/images/IDSN-logo.png)

**Estimated Time:** 60 minutes

## Overview

In this project, we use the embedded Watson AI libraries to create an application that performs emotion detection and sentiment analysis on a given text.

The application analyzes text and identifies the emotions expressed by the user, such as anger, disgust, fear, joy, and sadness. We then deploy the application as a web application using the Flask framework.

## Project Objectives

The main objective of this project is to build, package, test, and deploy an emotion detection application using Python and Flask.

## Tasks and Objectives

The project consists of the following eight tasks:

- **Task 1:** Clone the project repository.
- **Task 2:** Create an emotion detection application using the Watson NLP library.
- **Task 3:** Format the output of the application.
- **Task 4:** Package the application.
- **Task 5:** Run unit tests on the application.
- **Task 6:** Deploy the application as a web application using Flask.
- **Task 7:** Incorporate error handling.
- **Task 8:** Run static code analysis.

## Technologies Used

- Python 3
- Flask
- Watson NLP
- Requests
- HTML
- Git and GitHub
- Pytest / Unit Testing
- Pylint

## Project Structure

```text
oaqjp-final-project-emb-ai/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yunesmchaar/oaqjp-final-project-emb-ai.git
```

### 2. Navigate to the project directory

```bash
cd oaqjp-final-project-emb-ai
```

### 3. Install dependencies

```bash
python3 -m pip install requests flask
```

If a `requirements.txt` file is available, install the dependencies using:

```bash
python3 -m pip install -r requirements.txt
```

## Running the Application

Start the Flask server:

```bash
python3 server.py
```

Open the application in your browser using the URL displayed in the terminal.

The application allows users to enter text and receive an emotion analysis result.

## Emotion Detection

The application analyzes text and identifies the following emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

It also determines the dominant emotion based on the analysis results.

## Testing

Run the unit tests to verify that the emotion detection function works correctly:

```bash
python3 -m unittest
```

Or, if the project uses pytest:

```bash
pytest
```

## Static Code Analysis

Run Pylint to analyze the code quality:

```bash
pylint EmotionDetection
```

Static code analysis helps identify coding errors, potential bugs, coding standard violations, and improve code quality.

## Error Handling

The application includes error handling to manage:

- Empty text input
- Invalid requests
- API errors
- Connection errors
- Unexpected responses

## Learning Outcomes

By completing this project, you will learn how to:

- Build an emotion detection application using Python.
- Integrate Watson NLP services.
- Analyze emotions in text.
- Format and process API responses.
- Package Python modules.
- Write and execute unit tests.
- Deploy a web application using Flask.
- Implement error handling.
- Perform static code analysis using Pylint.
- Manage projects using Git and GitHub.

## Author

**Yunes Mchaar**

## Acknowledgements

This project is part of the IBM Skills Network / Coursera learning experience.

Thanks to IBM Skills Network and Coursera for providing the learning materials and project guidelines.

---

**Happy Coding!**
