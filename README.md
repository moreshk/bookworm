# Bookworm
<img width="450" alt="Screen Shot 2023-07-13 at 10 32 27 am" src="https://github.com/moreshk/bookworm/assets/4209287/0e293890-8a3b-4f13-808b-00dd761e29d0">

Welcome to the Bookworm repository! Bookworm is a Python Flask web application that serves as a voice-to-voice AI chatbot. It utilizes the Whisper API for transcribing voice to text, the OpenAI API for generating text responses, and the Eleven Labs API to convert text responses into voice.

## Demo

A working demo of the application can be viewed on YouTube: [Demo Video](https://youtu.be/jJtlxmP9XTg)

[![Demo Video](demo-thumbnail.png)](https://youtu.be/jJtlxmP9XTg)

## Setup Instructions

To set up the Bookworm app on your local machine, follow the steps below:

### Prerequisites

- Python 3.x
- pip package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/moreshk/bookworm.git
   ```

2. Navigate to the project directory:

   ```bash
   cd bookworm
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

1. Obtain API keys

   - Whisper API: Obtain your Whisper API key from the Whisper API provider.
   - OpenAI API: Obtain your OpenAI API key from the OpenAI API provider.
   - Eleven Labs API: Obtain your Eleven Labs API key from the Eleven Labs API provider.

2. Configure environment variables

   - Create a `.env` file in the project root directory.
   - Add the following environment variables to the `.env` file:

     ```bash
     WHISPER_API_KEY=your_whisper_api_key
     OPENAI_API_KEY=your_openai_api_key
     ELEVENLABS_API_KEY=your_elevenlabs_api_key
     ```

### Running the App

1. Start the Flask development server:

   ```bash
   flask run
   ```

2. Open your web browser and visit `http://localhost:5000` to access the Bookworm app.

3. You can also run the python script and access it at http://127.0.0.1:5000/

## Usage

- Upon accessing the app, you can interact with the AI chatbot by providing voice input.
- Speak clearly into your microphone and wait for the app to transcribe your speech to text.
- The app will then generate a text response using OpenAI API and convert it to voice using the Eleven Labs API.
- You will hear the chatbot's response as voice output.

Feel free to explore and engage in conversations with the Bookworm voice-to-voice AI chatbot!

## License

[MIT License](LICENSE)

