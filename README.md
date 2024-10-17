# ollama-app-prompt-template

**Prompt Template: Developing a ChatGPT-like UI with Ollama and gemma2:2b
**

You are an architect with expertise in node and react.  You are going to develop a chatbot application with a user interface similar to ChatGPT. 

lets use Ollama with the gemma2:2b model for the backend and consume the api end point as http://localhost:11434/api/generate. Please provide detailed, step-by-step guidance on how to build this application, including code snippets where appropriate. The application should have the following features and requirements:

Environment Setup:

Instructions for installing Ollama and pulling the model
Setting up a React project for the frontend
List of necessary dependencies


Backend Integration:
Setup a simple backend server using node, express to interface with Ollama
API endpoint for sending messages to the model and receiving responses


Frontend Development:
A clean, responsive UI design similar to ChatGPT
A message input field and send button
A scrollable message display area
Clear differentiation between user and bot messages
Do not directly interface with ollama, use the backend server to  communicate with ollama





Advanced Features:

Display of "thinking" status while waiting for a response
Calculation and display of total response time
Error handling and display of error messages in the UI


Styling:

Use of a CSS-in-JS solution like styled-components for styling
A clean, modern aesthetic similar to popular AI chat interfaces


Performance Considerations:

Efficient rendering of messages, especially for long conversations
Proper handling of asynchronous operations


User Experience Enhancements:

Auto-scrolling to the latest message
Ability to send messages using the Enter key

Easy to debug:
Add detailed logging for both backend and frontend layers.



Please provide detailed explanations and complete code  for each major component of the application. 
Include any best practices or potential pitfalls to be aware of during development. If there are multiple approaches to solving any particular aspect, please explain the pros and cons of each.
