# Text-Summarization-Model-Using-LLMs

## Introduction
`Text-Summarization-Model-Using-LLMs` is an innovative solution crafted to condense extensive texts into concise, insightful summaries. This project uniquely integrates the power of two Large Language Models (LLMs) - LLaMA and GPT-3.5, leveraging their advanced capabilities for text analysis and summarization. Designed to serve academics, professionals, and casual users alike, our model ensures quick comprehension of complex documents, articles, and reports, embodying the pinnacle of current AI text summarization technology.

## Features
- **Efficient Text Summarization**: Condense articles, reports, and conversations into short summaries without losing essential content.
- **Powered by LLMs**: Utilizes cutting-edge models like GPT-3.5/ Llama2 for superior text generation and summarization quality.
- **Web Application**: Features a Flask-based web application and Streamlit interface, making it accessible and user-friendly.
- **Cross-Platform Compatibility**: Designed for seamless operation across different platforms and devices.

## Setup and Installation
Get started with the `Text-Summarization-Model-Using-LLMs` by following these simple setup instructions:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/ambuj991/Text-Summarization-Model-Using-LLMs.git
    cd Text-Summarization-Model-Using-LLMs
    ```

2. **Install Required Packages**
    ```bash
    pip install transformers accelerate huggingface_hub flask flask-ngrok pyngrok==4.1.1 flask-cors
    ```

3. **Hugging Face Authentication**
    - Obtain a token from [Hugging Face](https://huggingface.co/settings/tokens).
    - Log in using `huggingface-cli login` and enter your token as prompted.

4. **Run the Flask App**
    ```bash
    flask run
    ```
    Follow the ngrok or Flask app instructions for local or public access.

5. **Streamlit App Execution**
    Ensure Streamlit is installed:
    ```bash
    pip install streamlit
    ```
    Execute the Streamlit application:
    ```bash
    streamlit run your_streamlit_app.py
    ```



## Contributing
We welcome contributions to enhance `Text-Summarization-Model-Using-LLMs`. Whether it's feature improvements, bug fixes, or documentation, your help is appreciated. Please read through our contribution guidelines for more details on submitting pull requests.



## Acknowledgements
- [OpenAI](https://openai.com/) for their LLMs.
- [Hugging Face](https://huggingface.co/) for the model hosting.
- [Flask](https://flask.palletsprojects.com/) for the web framework.
- [Streamlit](https://streamlit.io/) for creating interactive web apps.

