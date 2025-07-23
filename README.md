# BakBak - Java Chat Application

**BakBak** is a terminal-based chat application built in Java using socket programming. It features real-time messaging, user-to-user and group messaging, image sharing via links, and basic GUI elements with `JavaFX`. It includes a multithreaded server architecture to support multiple clients concurrently.

## Features

- One-to-one private messaging
- Group chat functionality
- Image sharing (sent as clickable links)
- Chat history storage using a relational database (SQLite)
- Multithreaded server to handle 100+ concurrent clients
- JavaFX-based GUI on client side (in progress)
- Link-click functionality opens image in a separate view
- Basic message formatting (user, timestamp, group/private)

## Technologies Used

- **Java** (Core, Sockets, Threads)
- **JavaFX** (Client GUI)
- **SQLite** (BLOB-based message storage)
- **Maven** (Dependency management)
- **FXML** (for JavaFX GUI layout)

## Folder Structure

| File / Folder           | Purpose                                                    |
|-------------------------|------------------------------------------------------------|
| `client/`               | JavaFX GUI for client-side interface                        |
| `server/`               | Java server code with multithreaded client handling         |
| `database/`             | SQLite schema and database integration files                |
| `assets/`               | UI icons, sample images, and static resources               |
| `ChatClient.java`       | Main entry point for the chat client (non-GUI version)      |
| `ChatServer.java`       | Core multithreaded server implementation                    |
| `README.md`             | Project documentation                                       |

# How to Run

To compile and launch the chat application components, follow the steps below:

## 1. Start the Server

To run it change the IP address in both ./src/chatClient.java and in ChatServer.class

Use the batch file `cs.bat` to compile and run the server:

```bash
./cs.bat
```


## 2. Launch the Client

Use the batch file `run.bat` to run the JavaFX-based client:
```bash
./run.bat
```

# License

This project is licensed under the **MIT License**.

---

# Author
**HuntSky**  
Email: [huntdev12@gmail.com](mailto:huntdev12@gmail.com)  
