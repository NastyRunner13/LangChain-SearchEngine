# Langchain-SearchEngine

Langchain-SearchEngine is a Streamlit-based application that combines the power of language models with various search tools to provide an interactive chat interface with web search capabilities.

Check out the app here -> https://langchain-searchengine.streamlit.app/

## Features

- Chat interface powered by Groq's language models
- Integration with DuckDuckGo for web searches
- Access to Wikipedia and arXiv for academic and encyclopedic information
- Streamlit-based user interface for easy interaction

## Prerequisites

Before running the application, make sure you have the following:

- Python 3.7+
- Groq API key

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/NastyRunner13/LangChain-SearchEngine.git
   cd Langchain-SearchEngine
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the Langchain-SearchEngine:

1. Open a terminal and navigate to the project directory.

2. Run the following command:
   ```
   streamlit run app.py
   ```

3. Open a web browser and go to the URL displayed in the terminal (usually `http://localhost:8501`).

4. In the sidebar, enter your Groq API key.

5. Start chatting and asking questions in the input box at the bottom of the page.

## Usage

- Type your questions or prompts in the chat input box.
- The application will use various search tools (DuckDuckGo, Wikipedia, arXiv) to find relevant information.
- The AI will provide responses based on the search results and its language understanding capabilities.

## Note

Make sure to keep your Groq API key confidential and do not share it publicly.

## Contributing

Contributions to improve Langchain-SearchEngine are welcome.
