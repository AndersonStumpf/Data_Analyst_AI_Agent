# Clippy AI - Voice Assistant for Car Sales Data Analysis

Clippy AI is an interactive voice assistant that uses Artificial Intelligence to answer questions about a car sales dataset. It combines speech recognition, natural language processing, and speech synthesis to provide a seamless and intuitive experience.

## Features
- **Voice interaction:** Use a keyboard shortcut to speak with the AI.
- **Data analysis with Pandas:** The agent analyzes the car sales dataset and answers your questions.
- **Audio transcription:** The Whisper model converts your spoken questions into text.
- **Voice responses:** OpenAI's speech synthesis model transforms responses into audio.

## Technologies Used
- **Python**
- **OpenAI GPT-4o**
- **Whisper (speech recognition model)**
- **Pandas (for data analysis)**
- **LangChain (for AI agent creation)**
- **SoundDevice (for audio recording and playback)**
- **pynput (for keyboard control)**

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/clippy-ai.git
   cd clippy-ai
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key:
   - Create a `.env` file in the project root and add your API Key:
     ```
     API_KEY=your_openai_api_key
     ```
4. Add the car sales dataset to the project root:
   - File name: `car_price_dataset.csv`

## How to Use
1. Run the main script:
   ```bash
   python main.py
   ```
2. Press **Ctrl** to start or stop recording.
3. Ask your question and wait for the AI's voice response.

## Example Questions
- "What is the most expensive car in the dataset?"
- "How many cars were sold in 2023?"
- "What is the average car price?"

## Contribution
Feel free to contribute with improvements, fixes, or new features. Just open a pull request or report issues in the issues tab.

## License
This project is licensed under the [MIT License](LICENSE).

