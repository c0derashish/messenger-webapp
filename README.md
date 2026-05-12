# Messenger-WebApp

Real-time messaging web application built with Flask, Socket.IO, SQLAlchemy, and MySQL. Messenger-WebApp supports live messaging, authentication, unread message tracking, dark mode, and responsive chat UI with real-time communication using WebSockets.

---

## Features

- Real-time messaging with Socket.IO
- User authentication system
- Secure password hashing
- Unread message counter
- Responsive chat interface
- Dark mode support
- Persistent chat history
- MySQL database integration
- Mobile-friendly UI
- Live message synchronization
- Docker and Google Cloud deployment support

---

## Tech Stack

### Backend
- Python
- Flask
- Flask-SocketIO
- SQLAlchemy
- MySQL
- Eventlet

### Frontend
- HTML
- CSS
- JavaScript
- Socket.IO Client

---

## Project Structure

```text
Messenger-WebApp/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── app.yaml
├── .gitignore
│
├── templates/
│   ├── login.html
│   ├── signup.html
│   └── chat.html
│
├── static/
│   ├── style.css
│   ├── script.js
│   └── images/
│
└── .env
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/c0derashish/messenger-webapp
cd Messenger-WebApp
```

---

### Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

#### Windows
```bash
.venv\Scripts\activate
```

#### Linux / Mac
```bash
source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file:

```env
SECRET_KEY=your_secret_key

DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=your_database_host
DB_NAME=your_database_name

SQLALCHEMY_DATABASE_URI=mysql+pymysql://user:password@host:3306/dbname

UPLOAD_FOLDER=static/uploads
```

---

## Run the Application

```bash
python app.py
```

Application will run on:

```text
http://127.0.0.1:5000
```

---

## Main Functionalities

### Authentication
- User signup
- User login
- Secure password hashing
- Session-based authentication

### Real-Time Messaging
- Instant message delivery
- Live message updates
- Socket.IO broadcasting
- Persistent message storage

### Chat Features
- Unread message tracking
- Dynamic chat loading
- User selection sidebar
- Message timestamps
- Auto scroll behavior

### Responsive UI
- Mobile-friendly layout
- Dark mode toggle
- Modern chat interface
- Smooth transitions

---

## Deployment

This project supports:
- Docker deployment
- Google App Engine deployment

Configuration files:
- `Dockerfile`
- `app.yaml`

---

## Future Improvements

- Typing indicators
- Media sharing
- Voice messages
- Group chats
- Message reactions
- End-to-end encryption
- Online/offline presence
- Push notifications

---

## Screenshots

Add screenshots here:

![Login Page](screenshots/login.png)

![Signup Page](screenshots/signup.png)

![Chat Interface](screenshots/chat.png)






