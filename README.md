# Chat Application Project  

This project is a **real-time chat application** where users can connect and chat with each other. It includes features like user authentication, group chats, private messages, and multimedia sharing. The application uses **Spring Boot** for the backend, **SockJS** for WebSocket communication, and **React** for the frontend.

---

## Features  
- **User Login**: Users must log in with a username to join the chat.  
- **Real-Time Messaging**: Chat updates happen instantly for all participants in the chatroom.  
- **User Notifications**: Get alerts when someone new joins the chatroom.  
- **Private Messages**: Chat privately with other users.  
- **Multimedia Sharing**: Share photos, videos, and other files in the chat.  
- **User Logout**: Easily log out, and your username will be removed from the list of active participants.  

---

## Tech Stack  
This application uses the following technologies:  
- **Spring Boot**: Handles the backend functionality and business logic.  
- **SockJS**: Enables real-time communication using WebSocket or fallback mechanisms.  
- **React**: Powers the frontend user interface and interactions.  

---

## How to Run the Project Locally  

### Backend Setup (Spring Boot)  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/hemanthsaich/ChatApp-Springboot.git  ```
2. __Navigate to the project directory__: ```cd chatroom-backend```
3. __Set up the backend server__:
   - Install the necessary dependencies: ```mvn clean install```
   - Start the Spring Boot server: ```mvn spring-boot:run```
4. __Set up the frontend__:
   - Install the necessary dependencies: ```cd chatroom-ui``` && ```npm install```
   - Start the React development server: ```npm run dev```
5. __Open your web browser__ and visit ```http://localhost:5173``` to access the chat application.

## Screenshots
Here are some screenshots of the chat application:

1. Login Page 

2. Chat Page
- Chatroom ![Chat-1](https://github.com/user-attachments/assets/c2c5e09f-591b-4200-b001-e15f7fe2110a)


- Private Text ![Chat-2](https://github.com/user-attachments/assets/b6fa2fdd-31d4-4165-83b0-b971b71f36ce)


