# Llama Academy

This is a project about using the Llama3.1 model family as a teacher and quizzer for checking your understanding.

## Llama Academy

Llama Academy is an interactive educational application that uses AI to teach and quiz you on various topics. It features two key models: the Teacher and the Quizzer. Here's how it works:

- **Teacher Mode**: Explains concepts thoroughly, using examples and breaking down information into manageable chunks.
- **Quizzer Mode**: After learning, you can use the Take Quiz button to activate the Quizzer, which generates 5 multiple-choice questions based on your learning and chat history.

This project leverages state-of-the-art models and frameworks to deliver a seamless learning experience.

## Features

- **Teacher Mode**: Guides users with clear explanations and interactive learning.
- **Quizzer Mode**: Tests knowledge with personalized quizzes.
- **Audio Support**: Accepts audio input using the Whisper model.
- **Seamless Integration**: Uses Akash Chat API for AI responses.
- **User-Friendly Interface**: Built with Streamlit for an intuitive user experience.

## Technology Stack

- **Llama Models**: Power the teaching and quizzing functionality.
- **Whisper Model**: Handles audio input and converts speech to text.
- **Transformers**: Facilitates AI model interactions.
- **Librosa**: Processes audio inputs for Whisper.
- **Akash Chat API**: Retrieves responses from AI models.
- **Streamlit**: Provides the web-based user interface.

## Installation

Follow these steps to install Llama Academy locally:

### Prerequisites

- Python 3.8 or higher
- Docker and Docker Compose installed
- Basic knowledge of terminal/command-line operations

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/llama-academy.git
   cd llama-academy
