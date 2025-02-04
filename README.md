---

# **WebSocket Chatting Application with AI Support**

A real-time chat application built using **Spring Boot** and **WebSockets**, with **AI-powered message suggestions** integrated via the **Gemini API**. This project allows multiple users to join chat rooms, send messages, and receive intelligent AI-generated responses, enhancing the overall chat experience.
![Screenshot 2025-02-04 150604](https://github.com/user-attachments/assets/a58805c9-13ad-42d5-9050-cec7c91279f3)


---

## **Features**
![Screenshot 2025-02-04 181628](https://github.com/user-attachments/assets/2a34a332-112f-4b33-bafd-19b048696614)
- 🔴 **Real-Time Messaging:** Seamless communication using WebSockets and STOMP protocol.
- 👥 **User Management:** Users can join or leave chat rooms dynamically.
- 💬 **AI-Powered Replies:** Integrated **Gemini API** for generating smart reply suggestions.
- 🎨 **Responsive UI:** Clean and responsive user interface using **HTML**, **CSS**, and **JavaScript**.
- 📜 **Event Notifications:** Real-time user join/leave notifications.

---

## **Tech Stack**

- **Backend:**  
  - Java  
  - Spring Boot  
  - WebSocket (STOMP protocol)  

- **Frontend:**  
  - HTML, CSS, JavaScript  
  - **SockJS** and **STOMP.js** for WebSocket connections  

- **AI Integration:**  
  - **Gemini API** for AI-generated message suggestions  

---

## **Getting Started**

### **Prerequisites**

Ensure you have the following installed:

- **Java 11** or later  
- **Maven**  

---

### **Installation**

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/websocket-chat-app.git
   cd websocket-chat-app
   ```

2. **Backend Setup (Spring Boot)**  
   - Navigate to the project directory:
     ```bash
     cd src/main
     ```
   - Build and run the Spring Boot application:
     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend Setup**  
   - No complex setup needed, just open `index.html` in a browser or serve via a simple HTTP server.

4. **Configure AI API (Gemini)**  
   - Add your **Gemini API key** in the configuration file (e.g., `application.properties` or a separate config file):
     ```
     gemini.api.key=YOUR_API_KEY_HERE
     ```

---

## **Usage**

1. Open your browser and navigate to:  
   ```
   http://localhost:8080
   ```

2. Enter a username and start chatting in the chat room.

3. The AI will provide smart reply suggestions automatically during the conversation.

---

## **Project Structure**

```
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.swarup.chat
│   │   │       ├── ChatController.java
│   │   │       ├── WebSocketEventListener.java
│   │   │       └── config
│   │   ├── resources
│   │       ├── static
│   │       │   ├── css
│   │       │   │   └── main.css
│   │       │   └── js
│   │       │       └── main.js
│   │       └── templates
│   │           └── index.html
├── README.md
└── pom.xml
```

---

## **Contributing**

Contributions are welcome! 🎉

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a **Pull Request**

---

## **License**

This project is licensed under the **MIT License**.

---

## **Contact**

Created by **Swarup Kumar Sahoo**  
Feel free to reach out via [GitHub](https://github.com/swarup-kumar-sahoo) or open an issue for any questions!

---
