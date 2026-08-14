# 💬 Django Chat Application

A real-time web-based chat application built with **Django** and **Django Channels**. Users can log in, join public chat rooms, and exchange messages instantly using WebSockets.

## 🚀 Features

- 🔐 User authentication
- 🔑 Login and logout
- 💬 Real-time messaging
- ⚡ WebSocket communication
- 🏠 Multiple public chat rooms
- 👤 User-based message identification
- 📱 Responsive UI
- 🎨 Modern and professional interface
- 🔄 Automatic chat scrolling
- 🔒 CSRF protection
- 🌐 HTTP/HTTPS compatible WebSocket connection

## 🛠️ Technologies Used

- Python
- Django
- Django Channels
- Daphne
- WebSockets
- HTML5
- CSS3
- Bootstrap
- JavaScript
- SQLite

## 📁 Project Structure

```text
mychat/
│
├── chatapp/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html
│   │   ├── registration/
│   │   │   └── login.html
│   │   ├── room.html
│   │   └── rooms.html
│   ├── admin.py
│   ├── apps.py
│   ├── consumers.py
│   ├── models.py
│   ├── routing.py
│   ├── urls.py
│   └── views.py
│
├── mychat/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
