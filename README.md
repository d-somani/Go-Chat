Go-Chat
A lightweight, real‑time chat application backend written in Go (Golang) with SQLite for data persistence. This project demonstrates user authentication, message history, and user management in a simple, production‑style structure.

Project Structure
├── main.go         # Application entry point and HTTP router setup
├── auth.go         # Authentication logic (Login / Register)
├── db.go           # Database connection and initialization
├── models.go       # Data structures (User, Message structs)
├── user.go         # User profile management
├── userlist.go     # Logic to retrieve active users
├── history.go      # Chat history retrieval
├── static/         # Frontend assets (HTML, CSS, JS)
├── .env            # Environment configuration
├── chatapp.db      # SQLite database file
└── go.mod          # Go module definition

Features
1 User Authentication
2 Secure registration and login using standard Go web patterns.
3 Chat History
4 Persistent storage of chat messages using SQLite, with retrieval by user or conversation.
5 User Management
6 List active users.
7 Manage user profiles and metadata.
8 Static File Serving
9 Serves frontend assets directly from the static/ directory, making it easy to plug in a simple web UI.

Tech Stack
-Language: Go (Golang)
-Database: SQLite
-Configuration: Dotenv (.env) for environment management
