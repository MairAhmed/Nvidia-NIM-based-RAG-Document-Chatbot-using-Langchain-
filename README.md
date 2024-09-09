# Nvidia-NIM-based-RAG-Document-Chatbot-using-Langchain-

This application demonstrates how to use LangChain with NVIDIA's AI endpoints to generate answers from a set of documents. The app allows users to load a collection of PDFs, split the documents into manageable chunks, create embeddings using NVIDIAEmbeddings, and then query the embedded documents to retrieve relevant information.

# Features

Load documents from a directory of PDFs.

Split the documents into chunks for easier processing.

Create embeddings using NVIDIA's language models.

Ask questions about the loaded documents and receive accurate answers based on the content.

Display relevant document chunks with a similarity search feature.

# Hardware
The app relies on NVIDIA Embeddings, so using NVIDIA-compatible hardware is recommended.

# Installation

Clone this repository to your local machine.

Install the required dependencies by running:

pip install -r requirements.txt

Make sure to set up your NVIDIA API key. Create a .env file in the root of the project and add your key:

NVIDIA_API_KEY=your_key_here

Place your PDF files in the ./us_census directory for loading into the application.

# Usage
To start the application, run the following command:

streamlit run app.py

# Steps
Load Documents: Click on the "Documents Embedding" button to load the documents and create vector embeddings.

Ask a Question: Input your question in the text box, and the app will search through the embedded documents 
to retrieve relevant answers.

View Document Chunks: After getting an answer, expand the "Document Similarity Search" section to see the most relevant document chunks

# Environment Variables
Make sure you have the following environment variable:

NVIDIA_API_KEY: Your NVIDIA API key for authentication.

# Contributing
Feel free to open issues or submit pull requests if you'd like to contribute or report bugs.

# License
This project is licensed under the MIT License.



