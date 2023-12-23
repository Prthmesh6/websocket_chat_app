# WebSocket Chat Application

<div id="header" align="center">
  <img src="https://private-user-images.githubusercontent.com/74038190/241765440-80728820-e06b-4f96-9c9e-9df46f0cc0a5.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDMzNjY0NjQsIm5iZiI6MTcwMzM2NjE2NCwicGF0aCI6Ii83NDAzODE5MC8yNDE3NjU0NDAtODA3Mjg4MjAtZTA2Yi00Zjk2LTljOWUtOWRmNDZmMGNjMGE1LmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjIzVDIxMTYwNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJmMDA5ZjYyZmRiMGIyNzc0MDQ4Y2NlM2RkMmNkOWMyMjBiZTkxNGQwODcwNThiY2U0MzYyOGIyMGNmMGFkOTUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.IOs0uWLCWHLvdqWKcQ6AFACGS9FZ2ocRACaqETqTjBs" width="500"/>
</div>

Welcome to my WebSocket-based chat application! This project demonstrates a simple chat application using WebSocket technology.

### Documentation

- [WebSockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)

## Features

1. **Authentication:** Users can authenticate by providing their username and password. Only valid credentials allow the establishment of a WebSocket connection.
   
2. **Ping Pong Mechanism:** The application regularly sends ping messages to the server, expecting a pong response. If the server fails to respond within a defined timeframe or after a certain number of retries, the WebSocket connection is automatically terminated.
   
3. **Real-time Chat:** Once connected, users can join chat rooms and exchange messages. Messages sent by one user are instantly visible to all participants in the same chat room.

## Technologies Used

- **Backend:** Golang
- **Frontend:** HTML
- **WebSocket Protocol:** Utilizes the WebSocket protocol for real-time communication.

## How to Use

### Prerequisites

- Go and HTML should run on your machine

### Getting Started

1. Clone this repository.
2. Run command go run . in websocket_chat_app directory
   
### Authentication

- Users need to provide valid credentials to establish a WebSocket connection.
- For now keep username as "prathmesh" and password as "123"

### Chat Functionality

- Go on your localhost port 8080
- Users can join existing chat rooms or create new ones.
- Establish a websocket connection by authenticating
- Type a message in box and click on "send message" button

### Ping Pong Mechanism

- Client will send ping to server after every 5 seconds
- If server fails to Pong for 2 consecutive times, connection will be dropped

## Future Improvements

- This is a working Websocket chat app sample
- In Future I am going to build a proper authentication and maintainable code for this
- Database will be used to keep the user details


## Contact Information

For any inquiries or suggestions, feel free to contact me at,
<div id="badges">
  <a href="https://www.linkedin.com/in/prathmeshpatil64/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
