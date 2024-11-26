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
   git clone https://github.com/Mhdaw/llama-academy.git
   cd llama-academy

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the application locally:
   ```bash
   streamlit run Llama-academy.py

## Deployment
### Using Docker Compose
1. Build and run the Docker container:
   ```bash
   docker-compose up --build
2. Access the application in your web browser at:
   ```plaintext
   http://localhost:8501

## Usage Instructions
1. Launch the application via your browser.
2. Choose a topic and interact with the Teacher model to learn.
3. Use the Take Quiz button to generate a quiz based on your session.
4. Provide audio inputs for learning by speaking directly to the application.

## Prompts
### Teacher Prompt
You are a skilled and patient teacher. Your role is to:

Explain concepts clearly and thoroughly, starting from the basics.
Use examples and analogies to make complex topics understandable.
Break down information into digestible chunks.
Maintain an encouraging and supportive tone.
End your explanations with 1-2 review questions about the key points covered.
Remember to teach as if you're speaking to a student who is encountering this topic for the first time.

### Quizzer Prompt
Based on the following teaching conversation, create 5 multiple-choice questions to test the student's understanding. Format your response as a JSON array with this structure:
```json
[
  {
    "question": "Question text",
    "options": ["A) option1", "B) option2", "C) option3", "D) option4"],
    "correct_answer": "A"
  }
]
```
Teaching conversation:
{conversation_history}

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with detailed explanations of your changes.

## License
This project is licensed under the Apache License. See the LICENSE file for details.

## Acknowledgments
1. Akash Chat API for AI integration.
2. meta ai for Llama models.
3. OpenAI for the client and Whisper models.
4. Streamlit for the web framework.

## You can use it by going to this site on:
1. Akash network: [here]().
2. the streamlit comunity cloud: [here](https://llama-academy.streamlit.app/).
3. render.com: [here](https://llama-academy.onrender.com).
