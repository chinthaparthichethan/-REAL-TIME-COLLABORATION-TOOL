# -REAL-TIME-COLLABORATION-TOOL

##  *Name*: CHINTHAPARTHI CHETHAN  
## *Company*: CODTECH IT SOLUTIONS PVT. LTD  
## *ID*: CT12ITW  
## *Domain*: MERN STACK WEB DEVELOPMENT  
## *Duration*: JANUARY 5, 2025 – MARCH 5, 2025  
## *Mentor*: Neela Santhosh Kumar  

### Overview of the Project  
Project: **Real-time Collaborative Code Editor**  
This project involves building a **real-time collaborative code editor** using the **MERN stack** along with **WebSockets (Socket.IO)** for live collaboration. The application enables multiple users to edit the same document simultaneously, similar to Google Docs but for coding.  

### Features  
The **Real-time Collaborative Code Editor** includes the following features:  

- **User Authentication**: Secure login and registration system.  
- **Real-time Code Editing**: Multiple users can edit the same file live.  
- **Syntax Highlighting**: Supports various programming languages.  
- **Collaboration Tools**: Displays active users, tracks changes in real time.  
- **Database Storage**: Saves document history and user sessions in MongoDB.  
- **WebSocket Communication**: Ensures instant updates across all users.  

### Prerequisites  
- **Node.js & npm**: Install and set up Node.js on your system.  
- **MongoDB**: Set up a database for storing code files and user data.  
- **Basic MERN Stack Knowledge**  

### Step-by-Step Guide to Running the Code Editor  
#### Step 1: Clone the Repository  
```bash
git clone <repository_link>
cd collabedit
```
#### Step 2: Install Dependencies  
```bash
npm install
cd client
npm install
```
#### Step 3: Run the Server  
```bash
npm start
```
#### Step 4: Run the Frontend  
```bash
cd client
npm start
```
#### Step 5: Open the Collaborative Code Editor  
Access the application in your browser at `http://localhost:3000`.  

### Code Overview  
#### Backend  
- **Express.js & Socket.IO**: Handles real-time updates and user connections.  
- **MongoDB**: Stores saved code and user information.  
- **Authentication**: JWT-based authentication for security.  

#### Frontend  
- **React & CodeMirror**: Interactive UI with live syntax highlighting.  
- **State Management**: Uses Context API or Redux for user session management.  
- **WebSockets**: Enables instant updates across all connected users.  

### Conclusion  
This **Real-time Collaborative Code Editor** project provides an in-depth understanding of **real-time web applications**, **WebSocket communication**, and **full-stack development** using the **MERN stack**. It is a great learning experience for working with **live document collaboration and database integration**.  
