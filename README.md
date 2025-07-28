# WebSocket-Based Chess Game

This is a real-time two-player Chess game built with Node.js, Socket.IO, and Chess.js. The game allows two users to play on the same server port using WebSocket communication. The first user to join plays as white, and the second as black. Additional users are allowed to join as spectators.

This project is inspired by a tutorial from Sheriyans Coding School and aims to help understand the working of WebSockets and the `chess.js` library in a practical scenario.

## Project Goal

The main objective of this project is to:

- Understand the working of WebSocket communication using `Socket.IO`
- Learn how to manage real-time multiplayer game state
- Explore the capabilities of `chess.js` for move validation and FEN tracking
- Practice DOM manipulation with HTML, CSS (Tailwind), and JavaScript

## Tutorial Reference

This project is based on a YouTube tutorial by Sheriyans Coding School:  
[Watch on YouTube](https://youtu.be/CP7xxjuAJ0w?si=6oyCShhoNFKzHVzv)

## Tech Stack

- **Node.js** – Backend server runtime  
- **Express.js** – Web framework for Node  
- **Socket.IO** – For WebSocket-based communication  
- **Chess.js** – For game logic, move validation, and board state  
- **Tailwind CSS** – For styling the UI  
- **Vanilla JS + HTML** – For front-end structure and interaction  

## How It Works

1. Start the server (`node server.js` or `npm start`)
2. Visit the site in two different tabs or browsers:  
   - First visitor will be assigned the **white** pieces  
   - Second visitor will be assigned the **black** pieces  
   - Further visitors will join as **spectators**
3. Users can drag and drop pieces to play.
4. All moves are validated using `chess.js` and synchronized across clients via WebSocket.

## Real-Time Behavior

- Drag-and-drop supported chessboard
- Live piece updates across connected clients
- Role assignment: white / black / spectator
- Turn-based move restriction based on current player
- Board rotation for black player using CSS transform

## Features

- Real-time multiplayer over WebSocket
- Move validation with `chess.js`
- Spectator support
- Visual board flipping for black player
- Lightweight, responsive UI using Tailwind

## Results
### Starting of the Match
<img width="1356" height="713" alt="image" src="https://github.com/user-attachments/assets/ed319bef-a121-49d3-8f68-ce28b0a044f2" />

### Middle of the Match
<img width="1363" height="714" alt="image" src="https://github.com/user-attachments/assets/a89b3ea4-2650-462a-82a8-79c92deee043" />

## Proof of Completion
<img width="356" height="389" alt="image" src="https://github.com/user-attachments/assets/cdee1e9f-cba6-4f3e-a26f-7b9cbf2c11fa" />
