# Kronos AI

An AI-powered web platform designed to provide an intuitive interface for natural language conversations with an AI assistant focused on task automation.

## 📌 About the Project

**Kronos AI** is a web application developed as a study project to explore the development of AI-powered web platforms.

The platform allows users to interact with an AI assistant through **text and voice**, while also providing automation capabilities that enable the assistant to perform specific tasks.

The application combines a web-based frontend, a Django backend, an AI model accessed through an API, and automation functions into a single platform.

## ✨ Features

* 💬 Natural language conversations with an AI assistant
* ⌨️ Text-based interaction
* 🎙️ Voice-based interaction
* 🤖 Integration with an AI model through an API
* ⚙️ Task automation capabilities
* 🌐 Web-based interface
* 🔄 Communication between frontend and backend through requests
* 🧩 Modular backend architecture

## 🛠️ Technologies

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Django

### AI

* Groq AI model
* AI API integration

### Automation

* Python-based automation functions

## 🏗️ Architecture

The application follows a frontend/backend architecture:

```text
User
 │
 ├── Text Input
 │
 └── Voice Input
       │
       ▼
   Frontend
 HTML / CSS / JavaScript
       │
       │ HTTP Requests
       ▼
     Django
     Backend
       │
       ├───────────────┐
       ▼               ▼
   AI API        Automation
       │           Functions
       ▼               │
    AI Model           │
       │               │
       └───────┬───────┘
               ▼
          AI Response
               │
               ▼
            Frontend
               │
               ▼
              User




```

## 🔄 How It Works

1. The user sends a message through the web interface or interacts using voice.
2. The frontend processes the user's input.
3. The input is sent to the Django backend.
4. The backend communicates with the AI model through an API.
5. The AI processes the request and generates a response.
6. When necessary, automation functions can be used to perform specific tasks.
7. The resulting response is sent back to the frontend.
8. The user receives the AI assistant's response through the web interface.

## 🎯 Project Goals

The main goal of this project is to develop practical experience with:

* Web application development
* Backend development with Django
* Frontend development with HTML, CSS, and JavaScript
* API integration
* Generative AI
* Natural language processing concepts
* Voice interaction
* Task automation
* Communication between frontend and backend

## 🚧 Project Status

**In development**

This project is being actively developed as part of my studies. New features and improvements may be added as development progresses.

## 🔮 Future Improvements

Possible future improvements include:

* Additional automation functions
* Improved voice interaction
* More advanced AI assistant capabilities
* Conversation history
* User authentication
* Personalization features
* Improved mobile responsiveness
* Additional AI model integrations

## 👨‍💻 Author

Developed by **Ailan** as a study project focused on web development, Python, Django, artificial intelligence, and automation.

## 📄 License

This project is intended for educational and study purposes.
