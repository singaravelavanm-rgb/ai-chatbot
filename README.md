# AI Chatbot

A simple command-line chatbot built in Python that uses the Groq API to respond to user prompts.

## Features
- Interactive chat loop in the terminal
- Uses environment variables for API key management
- Simple, beginner-friendly implementation

## Requirements
- Python 3.9+
- A Groq API key

## Setup
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project root and add your API key:
   ```env
   GROQ_API_KEY=your_api_key_here
   ```
4. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Notes
- The script expects the API key to be available in the `.env` file.
- Type `exit` to stop the chat session.
