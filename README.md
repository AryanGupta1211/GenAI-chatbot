# Aryan's Chatbot

**Aryan's Chatbot** is a simple yet powerful application built with **Streamlit** and **Google Generative AI** (formerly known as Gemini Pro). This chatbot allows users to interact with an AI model, providing a conversational interface for generating content based on user input.

## Features

- **Interactive UI**: Streamlit provides an interactive web interface for the chatbot.
- **Chat History**: The application maintains a history of the conversation, allowing users to see past interactions.
- **Google Generative AI Integration**: Utilizes Google's Gemini Pro model to generate responses based on user input.

## Getting Started

### Prerequisites

- **Python 3.6 or higher**
- **Streamlit**
- **Google Generative AI Python library**

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/aryans-chatbot.git
    ```

2. Navigate to the project directory:

    ```bash
    cd aryans-chatbot
    ```

3. Install the required packages:

    ```bash
    pip install streamlit google-generativeai
    ```

### Configuration

Before running the application, you need to configure the Google Generative AI API key:

1. Obtain your API key from the Google Makersuite.
2. Create a `.env` file in the project root and add your API key:

    ```
    GOOGLE_GENERATIVEAI_API_KEY=your_api_key_here
    ```

## Usage

To run the chatbot application, execute the following command:

```bash
streamlit run app.py
