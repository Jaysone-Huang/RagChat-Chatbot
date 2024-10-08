# RagChat-Chatbot

A simple chatbot built using the RagChat API. This project demonstrates basic interaction with RagChat's language model, allowing users to have conversations directly through a terminal interface.

### Features:
- **RagChat Integration**: Leverages the RagChat API for natural language processing, enabling smooth and intelligent conversations with the chatbot.
- **Upstash Integration**: Utilizes Upstash for managing stateful interactions. Upstash provides serverless Redis, allowing the chatbot to maintain conversation history and session data efficiently. This integration ensures a seamless experience, even in distributed and scalable environments.
- **Next.js Interface**: Built with Next.js for a modern and efficient interface, allowing users to interact with the chatbot through a simple and accessible web-based UI.

### How It Works:
1. **Initialization**: The chatbot initializes by connecting to the RagChat API and setting up a Redis instance with Upstash to store session data.
2. **Conversation Handling**: User inputs are sent to the RagChat API, and responses are generated and stored in Upstash, preserving the context for ongoing conversations.

### Getting Started:
1. Clone the repository.
2. Set up your RagChat and Upstash API keys.
3. npm install all dependencies
4. npm run dev (side note, to feed information to the AI, it requires you to append the information link into the url ex. http://localhost:3000/https:/en.wikipedia.org/wiki/Alien:_Romulus)
6. ENJOY!

### Preview of My App:

<p align="center">
  <img src="./chatbot/public/emptyChat.JPG" alt="Empty Chat" width="450"/>
  <img src="./chatbot/public/chat.JPG" alt="Chat" width="450"/>
  <img src="./chatbot/public/chatSkinny.JPG" alt="Chat Skinny" width="450"/>
</p>


