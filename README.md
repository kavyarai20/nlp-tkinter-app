# NLP Desktop App (Tkinter + OOP)

This is a desktop NLP application built with **Python (Tkinter + OOP)**.  
It allows users to register/login and then perform:

- **Sentiment Analysis**
- **Named Entity Recognition (NER)**
- **Emotion Prediction**

---

## Project Structure
project-folder/
├── app.py # Main Tkinter app
├── myapi.py # NLP API functions (sentiment, NER, emotion)
├── mydb.py # Handles user database
├── db.json # Stores registered user data
├── resources/ # Contains favicon & other assets
└── README.md

## Features
- User registration & login
- Choose NLP task (Sentiment / NER / Emotion)
- Tkinter GUI
- Object-Oriented design

---
## Notes
- This project originally used an API (free service discontinued).
- `settings.config` and `db.json` are ignored from GitHub for security reasons.
- If you want to run the project:
  1. Create your own `settings.config` or `.env` with required variables.
  2. Create a `db.json` file (or use SQLite) for storing registered users.
