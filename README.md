 ## Networked Tic-Tac-Toe Game (Java GUI)

This is a **2-player socket Tic-Tac-Toe game** implemented in Java using Swing for the graphical interface and sockets for communication between a **server** and a **client**. Players can either host a game or join one using an IP address and port.

 **Note:** This repository does **not** include the images (X, O, and board graphics). You can use your own images and name them as specified below.

---

## Features

- Local multiplayer via socket networking (host/client model)
- GUI interface using Java Swing
- Click-based move interaction
- Visual winning line and win/draw messages
- Custom graphics for X and O (images required)

---

## Required Images

The game depends on the following images placed in the classpath (e.g., in the `resources/` folder):

| File Name        | Purpose          |
|------------------|------------------|
| `board.png`      | Background game board |
| `redX.png`       | Player X (variant 1) |
| `blueX.png`      | Player X (variant 2) |
| `redCircle.png`  | Player O (variant 1) |
| `blueCircle.png` | Player O (variant 2) |

You can download any X and O images from the internet, **rename them accordingly**, and place them in your project's `resources/` directory or the same location where your class files reside (depending on your build setup).

---

## How to Run

### Prerequisites

- Java 8 or higher
- An IDE like IntelliJ, Eclipse, or simply the command line
- Internet/network access if connecting remotely (ensure firewalls or NAT don't block ports)

### Steps

1. **Compile the code**  
   Make sure both server and client machines have the source code compiled.

2. **Run the server**  
   Launch one instance and choose `yes` when prompted to host. Enter the desired port number.

3. **Run the client**  
   Launch the second instance, choose `no`, and provide the server's IP address and port.

4. **Play the game!**  
   Once connected, take turns placing X's and O's.

---

##  Notes

- The server starts listening for a client on the selected port.
- The client must enter the correct IP and port of the host.
- The game ends when one player wins or the board is full.
- If communication is lost, an error will be shown and the game will stop.

---

## Learning Concepts

This project demonstrates:

- Java networking with sockets
- Swing GUI programming
- Threading for real-time interactivity
- Basic 2D graphics handling
- Game logic implementation (win conditions, tie, player turns)

---
