# Cybersecurity Awareness Bot

## Project Overview
This project is a C# console-based chatbot created for PROG6221 Part 1.  
The chatbot is designed to promote cybersecurity awareness by interacting with the user and answering basic cybersecurity-related questions.

## Features
- Plays a WAV voice greeting when the application starts
- Displays ASCII art as a cybersecurity-themed header
- Asks the user for their name and personalises the conversation
- Responds to basic cybersecurity questions
- Handles invalid or empty user input
- Uses coloured text, borders, spacing, and a typing effect for a better console user interface
- Uses classes and methods for improved structure and readability
- Includes GitHub Actions for Continuous Integration (CI)

## Cybersecurity Topics Covered
- Password safety
- Phishing
- Safe browsing
- Online scams
- Privacy

## Project Structure
```text
CybersecurityAwarenessBot/
│
├── Program.cs
├── Chatbot.cs
├── AudioPlayer.cs
├── UserInterface.cs
├── ResponseHandler.cs
├── InputValidator.cs
├── README.md
│
├── Assets/
│   ├── welcome.wav
│   └── ascii-logo.txt
│
└── .github/
    └── workflows/
        └── dotnet-ci.yml
