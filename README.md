# Llama 2 🦙 Chatbot Documentation

This documentation explains the structure and functionality of the Llama 2 Chatbot Streamlit app.

## Introduction

The Llama 2 Chatbot is powered by [Replicate](https://replicate.ai/) and Streamlit. It allows you to interact with a conversational AI model called Llama2-7B or Llama2-13B.

## Setup

### Replicate Credentials

To use this app, you need to provide your Replicate API token. If you have it, simply enter it; otherwise, follow these steps:
1. Enter your Replicate API token in the input field.
2. Ensure that the token starts with 'r8_' and has a length of 40 characters.
3. Once entered, click 'Proceed to entering your prompt message!'

### Models and Parameters

- Choose a Llama2 model: You can select either 'Llama2-7B' or 'Llama2-13B'.
- Temperature: Adjust the response generation temperature between 0.01 and 5.0.
- Top-p: Control the diversity of responses with a value between 0.01 and 1.0.
- Max Length: Set the maximum length of generated responses between 32 and 128 characters.

## Chat Interface

- You can enter your message in the chat input field.
- Click 'Clear Chat History' to clear the chat history.
- Messages from the assistant will appear on the right, and user messages on the left.

## Generating Responses

The app uses the Llama2 model to generate responses based on user input. It follows a conversation format with alternating user and assistant messages.

- The assistant message format: "Assistant: [generated content]"
- The user message format: "User: [user input]"

## Functionality

- If you provide a user prompt, the assistant will respond accordingly.
- The app ensures that the assistant responds only once per message.
- The assistant's response is generated based on the conversation history.


---

**Note:** Ensure that you have set up the Replicate API token and chosen the desired model and parameters before using the chatbot.

Enjoy using the Llama 2 Chatbot! 🦙💬
