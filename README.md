# FAISS-HuggingFace-RAG

# Medical Bot Using Llama Model and Chainlit App

The Medical Bot is a tool designed to provide medical information by answering user queries using state-of-the-art language models and vector stores. 
This README will guide you through the setup and usage of the Llama2 Medical Bot.

## Table of Contents

- [Introduction](#langchain-medical-bot)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Prerequisites

Before you can start using the Llama2 Medical Bot, make sure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for PDF document loading)

## Installation

1. Clone this repository to your local machine.

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

5. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Getting Started

To get started with the Llama2 Medical Bot, you need to:

1. Set up your environment and install the required packages as described in the Installation section.

2. Configure your project by updating the `DB_FAISS_PATH` variable and any other custom configurations in the code.

3. Start the bot by running the provided Python script i.e ingest.py.

4. Now use the command to run the chainlit app
     chainlit run model.py -w

## Usage

The Llama2 Medical Bot can be used for answering medical-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a medical-related query to the bot.

3. The bot will provide a response based on the information available in its database.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

   ![image](https://github.com/Manojcr06/FAISS-HuggingFace-RAG/assets/67838014/f3842971-510c-4f9c-acc4-17a55baaf9e1)

## LangChain Retreival QA using Faiss DB as retreiver for the vectors

   ![image](https://github.com/Manojcr06/FAISS-HuggingFace-RAG/assets/67838014/ab3e413c-2bc5-4b72-977c-f4ce5889d82a)
   
## Backend Image of the script analysing/getting the semantic query vectors the Faiss DB 

   ![image](https://github.com/Manojcr06/FAISS-HuggingFace-RAG/assets/67838014/aa35573c-dce2-4f0c-ae26-c5567699ee3e)

## End Results

   ![image](https://github.com/Manojcr06/FAISS-HuggingFace-RAG/assets/67838014/7db8f596-5e96-41c7-9f1c-97039582bb00)


   



