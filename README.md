# Voice Assistant

## Overview

This Voice Assistant application:
- **Recognizes speech** and converts it to text.
- **Speaks responses** using `pyttsx3`.
- **Generates images** or responses via the DynaSpark API based on user commands.

## Features

- Time-based greetings
- Image generation for keywords like "image" or "design"
- Text-based responses
- Exit command ("exit" or "quit")

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Install dependencies:
   ```bash
   pip install speech_recognition pyttsx3 dynaspark
   ```
3. Set up your DynaSpark API key in the script.

## Usage

Run the application:
```bash
python ai.py
```
Speak commands into the microphone. Use "exit" or "quit" to stop.
