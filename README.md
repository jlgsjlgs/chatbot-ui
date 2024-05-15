# Chatbot Interface

This repository contains the ReactJS frontend code for a chatbot interface. This application allows users to interact with the chatbot through a simple web interface.

## Features

- **Interactive Chat Interface**: Allows users to send and receive messages from the chatbot.
- **Reset Chat**: Provides an option to reset the chat and start a new conversation.
- **Confirmation Dialog**: Confirms user's action before resetting the chat.

## Technologies Used

- **ReactJS**: JavaScript library for building user interfaces.
- **Material-UI (MUI)**: React component library for implementing Google's Material Design.
- **Axios**: Promise-based HTTP client for making API calls.

## Project Structure

- `src/components/ChatUI.js`: Main component for the chat interface.
- `src/components/ConfirmationDialog.js`: Component for the confirmation dialog used when resetting the chat.

## Usage

- **Sending a Message**: Type a message in the input field and press Enter or click the Send button.
- **Resetting the Chat**: Click the "Reset Chat" button in the AppBar. Confirm the action in the dialog that appears.


## Getting Started

### Prerequisites

- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/asknarelle-chatbot.git
   cd asknarelle-chatbot
   ```

2. Install dependencies:

   ```bash
    npm install
    ```

3. Run application:

   ```bash
    npm start
    ```