# Langchain Demo with LLAMA2

This project demonstrates the use of Langchain with the LLAMA2 model to create a simple interactive application using Streamlit. The application allows users to input a query and get responses from the LLAMA2 model.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/sahiltr/langchain-demo.git
    cd langchain-demo
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables:
    - Create a `.env` file in the project root and add your API keys:
        ```plaintext
        OPENAI_API_KEY=your_openai_api_key
        LANGCHAIN_API_KEY=your_langchain_api_key
        ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and navigate to `http://localhost:8501` to use the application. You can enter a query in the input field and get responses from the LLAMA2 model.



