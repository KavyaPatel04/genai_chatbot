# AI Chat Assistant

This is a Streamlit web application that provides an AI-powered chat interface using Azure OpenAI.

## Prerequisites

- Python 3.7+
- An Azure OpenAI account and credentials.

## Setup

1.  **Clone the repository (optional):**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-directory>
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure environment variables:**
    Create a file named `.env` in the root of the project and add the following variables with your Azure OpenAI credentials:

    ```
    AZURE_OPENAI_ENDPOINT="your_azure_openai_endpoint"
    AZURE_OPENAI_API_VERSION="your_api_version"
    AZURE_OPENAI_API_KEY="your_api_key"
    AZURE_OPENAI_DEPLOYMENT_NAME="your_deployment_name"
    ```

## Running the Application

You can run the application using the provided startup script:

```bash
./startup.sh
```

Alternatively, you can run it directly with Streamlit:

```bash
streamlit run app.py
``` 