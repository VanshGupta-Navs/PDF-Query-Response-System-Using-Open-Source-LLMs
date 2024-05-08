# PDF-Query-Response-System-Using-Open-Source-LLMs
Chat with Chatbot about PDF
This repository hosts a Python project enabling users to engage in a conversation with a chatbot regarding the uploaded PDF. By leveraging Python and the Streamlit framework, the project allows for seamless interaction and the generation of a PDF transcript of the conversation.

Installation
To run this project, please follow these steps:

Clone the repository:
bash
Copy code
git clone git@github.com:MattLondon101/chat-pdf-hugginface.git
cd chat-pdf-hugginface
Optionally, create and activate a conda virtual environment:
bash
Copy code
conda create -n env1 python=3.10
conda activate env1
Install the dependencies from the requirements.txt file:
bash
Copy code
pip install -r requirements.txt
Acquire a Hugging Face Hub API token. Visit Hugging Face, sign up for an account, and navigate to Settings > Access Tokens. Generate a new token. Then, create a .env file in this directory with the following content, replacing token with your actual token:
makefile
Copy code
HUGGINGFACEHUB_API_TOKEN = "token"
Save the .env file. The .gitignore file will ensure that the .env file is ignored for Git operations.
Running the Project
Once the dependencies are installed, run the project using Streamlit, which should have been installed via requirements.txt. Streamlit simplifies the creation of interactive web applications in Python.

To start the application, execute the following command:

bash
Copy code
streamlit run app.py
This command initiates the Streamlit server and opens the application in your default web browser. From there, you can engage in conversation with the chatbot regarding the uploaded PDF and generate a PDF transcript of the dialogue.

Enjoy exploring and interacting with the chatbot!
