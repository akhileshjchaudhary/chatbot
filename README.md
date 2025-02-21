# chatbot
Chatbot Backend Application (Basic Version)

This is a backend application for a chatbot, built using Spring Boot. The application allows users to register, log in, and interact with a chatbot. The chatbot uses an external API (Gemini API) to provide AI-generated responses to users' questions. This backend also stores user interactions (chat history) in a database.

Features
User Registration: Users can register with a username and password.
User Login/Logout: Users can log in and log out, with session management.
Chat Interaction: Users can ask questions to the chatbot and receive AI-generated responses.
Chat History: Users can view their previous interactions with the chatbot.

Technology Stack
Spring Boot: For building the backend services.
Spring Data JPA: For database interaction.
RestTemplate: For making HTTP requests to the Gemini API.
MySql Database: Used for storing user information and chat history.