# Gen-AI-Projects
Gen AI Projects
QuestiBot_Project
Introduction
The QuestiBot has been build using Python application that allows users to chat with their own data. Users can ask questions about the data using natural language, and the application will provide relevant responses based on the content of the data. This app utilizes a language model to generate accurate answers to users queries. Please note that the app will only respond to questions related to your own loaded data.

This is Generative AI FAQ Chatbot Project. You will find following five modules:

QA_on_PDF
QA_on_Web
QA_on_Image
QA_on_Audio
QA_on_Video
UI Diagram
Questibot UI Diagram

Technical Diagram
Questibot Technical Diagram

How It Works (Technical Details)
The application follows these steps to provide responses to your questions:

Data Loading: The app reads uploaded data and extracts their text content.

Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the uploaded data.

Dependencies and Installation
To install the MultiPDF Chat App, please follow these steps:

Clone the repository to your local machine.

Install the required dependencies by running the following command:

pip install -r requirements.txt
Obtain an API key from OpenAI and add it to the .env file in the project directory.

Usage
To use the QuestiBoat GenAI ChatBot, follow these steps:

Ensure that you have installed the required dependencies and added the OpenAI API key to the .env file.

Navigate to project folder using following command:

cd folder_location/GenAI_Chatbot
Run the Dashboard.py file using the Streamlit CLI. Execute the following command:

streamlit run Dashboard.py
The application will launch in your default web browser, displaying the user interface.

Select your module as per your data format (like .pdf, .jpg, .wav or web link)

Upload or paste your link (as per you module) into the chatbot.

Click on process and wait for processing to complete.

Ask questions in natural language about the loaded data using the chat interface.
