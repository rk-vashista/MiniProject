# **🛠️ AI-Powered Conversational Assistant**

An intelligent and interactive AI assistant built with **Flask**, **Socket.IO**, and **LangChain**, capable of engaging in conversations, analyzing images, generating content, and even manipulating spreadsheets. This assistant brings together natural language processing and fun, functional tools for an engaging user experience.

## **🚀 Features**

- **Conversational AI**: Chat with a friendly, markdown-formatted AI that can answer questions, provide information, and maintain conversations.
- **Image Upload & Analysis**: Upload images to the AI, ask questions, and receive insightful responses based on the content of the images.
- **Spreadsheet Manipulation**: Effortlessly manage and manipulate Google Spreadsheets or Excel files using the power of LLM and app scripts.
- **Tool Calls**: Perform various operations such as image generation, fetching cat and dog images, rolling dice, flipping coins, and more using predefined commands.
- **Interactive Games**: Play guessing games, roll dice, or flip coins directly in the chat with the AI.
- **Markdown Support**: The AI structures responses in markdown for clean and visually appealing conversations.
- **Image Generation**: Generate images based on user prompts using diffusion models.
- **Music Playback**: Command the AI to play music from YouTube or stop playback when desired.


## **🛠️ Setup & Installation**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd your-repo-name
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your environment variables:**

   Create a `.env` file in the root directory and add your API keys:

   ```bash
   GROQ_API_KEY=your_groq_api_key
   ```

5. **Run the app:**

   ```bash
   python app.py
   ```

   The app will run on `localhost:8080` by default.

## **🌟 Usage**

- **Chat with the AI**: Start typing in the chatbox on the web app and engage with the assistant.
- **Upload Images**: You can upload images to the assistant and ask it questions about the content.
- **Generate Images**: Use the `/imagine` command followed by a prompt to generate AI-created images.
- **Manipulate Spreadsheets**: Use the AI to automate and manipulate spreadsheet tasks via its LLM-driven capabilities.
- **Games & Fun**: Try out games like number guessing, dice rolling, and coin flipping.
  
## **💡 Commands**

Here are some of the commands you can use with the AI:

- `/cat`: Get a random cat image.
- `/dog`: Get a random dog image.
- `/imagine <prompt>`: Generate an image based on the given prompt.
- `/gtn`: Start a number guessing game.
- `/dice <sides>`: Roll a dice with the specified number of sides (default is 6).
- `/flip`: Flip a coin.
- `/play <query>`: Play music from YouTube.
- `/stop`: Stop the music playback.

## **🖼️ Image Upload and Analysis**

- Upload an image, and the AI will acknowledge the upload and allow you to ask questions about the image. It leverages Groq's image analysis models to provide detailed insights.

## **🔍 Spreadsheet Manipulation**

- Use the conversational AI to interact with and manipulate spreadsheet data, thanks to app script integration. Automate tasks like data entry, analysis, and formatting through simple chat commands.

## **🔧 Technologies Used**

- **Flask**: Backend web framework for Python.
- **Socket.IO**: Real-time, bidirectional communication between clients and servers.
- **LangChain**: A framework for building applications with LLMs (Large Language Models).
- **Groq**: Powering the AI's ability to analyze images and generate text/image responses.
- **PIL (Python Imaging Library)**: For image processing tasks.
- **Markdown**: Formatting messages for clean, readable output.


## **📄 License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
