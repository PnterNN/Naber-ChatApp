# Naber (Chatting Application)

**Naber** is a comprehensive chatting application that combines multiple projects, including a server, client, and mobile client. It is developed as part of a final-year project for Socket Programming and Service-Based Applications in C#, and also as a mobile application in Java.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Group Members](#group-members)
4. [Demo](#demo)
5. [How to Run](#how-to-run)
6. [Technologies Used](#technologies-used)

## Project Overview
The **Naber Chatting Application** consists of three main components:
1. **ChatApp Server**: Handles the core logic for message delivery, user authentication, and server management.
2. **ChatApp Client**: Provides a user-friendly interface for chatting, sending messages, and managing contacts.
3. **ChatApp Mobile Client**: A mobile version of the client, built using Java, enabling users to chat from their mobile devices.

The application supports features like real-time messaging, user authentication, and profile management, while also focusing on encryption for secure communication.

## Features
- **User Authentication**: Sign in and sign up functionality to allow users to authenticate and access their account.
- **Real-Time Messaging**: Send messages instantly to users, with options to send to specific users or to the "Everyone" group.
- **User Profiles**: Users can manage their profiles, update their usernames and email addresses.
- **Encryption**: Uses secure encryption methods to ensure the confidentiality of messages.
- **Message History**: Users can view their past messages with specific contacts.
- **Server Management**: The server manages all user connections and handles the transmission of messages.

## Group Members
- **Berkay Gümrükçü**
- **Kubilay Baltaoğlu**
- **Abdullah Bahar**
- **Batuhan Kürklü**
- **Ömer Batuk**
- **Abdulkadir Kutludoğmuş**
- **Zeynep Buse Rençber**
- **Eda Aslan**
- **Belinay Dinlemez**

## Demo
![chat_page](https://github.com/PnterNN/JavaProject---Client/assets/73419655/e9682e93-f789-4edb-989c-554aaa448ef5)
*Chatting interface of the application.*

![tweet_page](https://github.com/PnterNN/JavaProject---Client/assets/73419655/91cdbffa-7c4e-4ae3-b4c1-853d84f68883)
*Another view of the user interface.*

![sign_in](https://github.com/PnterNN/JavaProject---Client/assets/73419655/d120269d-a405-4df6-a688-389e9f56344c)
*Sign-in page.*

![sign_up](https://github.com/PnterNN/JavaProject---Client/assets/73419655/b6006e0e-9e65-44ef-afc0-a79f5378c229)
*Sign-up page.*

![profile_page](https://github.com/PnterNN/JavaProject---Client/assets/73419655/17821856-8b79-4f67-b0dd-02a8a74470e0)
*User profile page.*

## How to Run

### Prerequisites
1. **.NET SDK** (for server-side project)
2. **Java SDK** (for mobile client)
3. **MySQL** (optional, for persistent message storage)

### 1. Clone the Repository

```bash
git clone https://github.com/PnterNN/Naber-Chatting-Application
cd Naber-Chatting-Application
```

### 2. Run the Server
In the terminal, navigate to the server project directory and run the following command:

```bash
dotnet run
```

### 3. Run the Client (Desktop Application)
Open the client project in Visual Studio (or your preferred IDE) and run the application. This will launch the desktop client where users can sign in, sign up, and start chatting.

### 4. Run the Mobile Client
For the mobile client, open the project in Android Studio or any compatible Java IDE and run the app on an Android emulator or a physical device.

### Technologies Used

- **C#** for the server and desktop client.
- **Java** for the mobile client.
- **Socket Programming** for communication between server and clients.
- **MySQL** (optional) for storing user data and message history.
- **AES Encryption** for secure message transmission.
