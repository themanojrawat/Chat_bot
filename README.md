# Langchain with LLAMA3.1 API

This is a Streamlit application that uses Langchain with the LLAMA3.1 API to provide responses to user queries.

## Features

- Uses Langchain's `ChatPromptTemplate` for creating prompt templates.
- Utilizes `Ollama` for the LLAMA3.1 language model.
- Parses output using `StrOutputParser`.
- Interactive user interface built with Streamlit.

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/themanojrawat/Chat_bot.git
   cd Chat_bot
2. Create and activate a virtual environment:
    python -m venv venv
    .\venv\Scripts\activate

3. Install the required packages:
   pip install -r requirements.txt

4. Create a .env file in the root directory and add your Langchain API key:
   LANGCHAIN_API_KEY=your_api_key_here

5. Usage
Run the Streamlit app:
  streamlit run app.py

Interact with the app:

Enter a topic or question in the text input field.
The app will use the LLAMA3.1 model to generate a response.
File Structure
app.py: Main application file.
requirements.txt: List of required Python packages.
.env: Environment variables file (not included in the repository).
