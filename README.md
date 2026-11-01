# CS-19300-Final-Project
# Project Name

Multiplayer Connect Four across different machines

## The Problem

Can't play connect four without being in person. 
Can't play without buying the physical game.

## How It Works

Uses threads to have one machine create the server and join as a client. Another machine can then join the server. Each client will wait on the other to make a move. Win conditions are checked every turn and a draw happens when there are no more moves available.

![System diagram](docs/diagram.png)

## Tech Stack

- **Language:**  Java
- **Libraries:** Scanner, BufferedReader, PrintWriter
- **External tools:** None

## Setup



```java
git clone https://github.com/you/my-project
cd my-project
```

## Usage

How to actually run the thing, with examples.

```java
javac Connect4Server.java
java Connect4Server.java
javac Connect4Client.java
java Connect4Client.java (IP Address) (Port number)
// On another machine
javac Connect4Client
java Connect4Client (IP Address) (Port number)
```

## Roadmap

Features you haven't built yet but plan to (pull these from your
"Schedule" quadrant in the Eisenhower Matrix).

- [ ] Create server and clients
- [ ] Add move history
- [ ] Add draw and move undo proposals

## Author

Kevin Gu, https://github.com/Kevin4615
