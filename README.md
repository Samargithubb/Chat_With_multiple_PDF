# Chat_With_multiple_PDF

## Introduction
------------
### This is Chat_With_Multiple_PDF application which is created to chat with multiple PDF. THis is Python Application which is developed with Langchain framework, HuggingFace and Streamlit. With the help of this application you can ask any queries related to the pdf and application will return most accurate result to the queries.
## How it Works?
------------
![MultiPDF Chat App Diagram](./docs/LangChain-PDF-Architecture.jpg)
This application follows given steps to give answer to your queries related to PDF
1. PDF Processing: This application is designed to handle the loading and processing of multiple PDF documents, extracting their textual content efficiently.

2. Text Segmentation: The extracted text undergoes a segmentation process, breaking it down into smaller, more manageable chunks that are ready for further processing.

3. Linguistic Model: Employing a sophisticated language model, the system generates vector representations (embeddings) of these segmented text portions.

4. Semantic Matching: In response to your queries, the app conducts a comprehensive semantic analysis. It matches your question against the segmented text chunks, pinpointing the ones that hold the highest semantic similarity.
5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

## What is Langchain ?
------------
LangChain is a framework designed to simplify the creation of applications using large language models (LLMs). It provides a number of features that make it easier to develop applications that are data-aware and agentic, meaning that they can connect to other sources of data and interact with their environment. LangChain is open source and available on GitHub.

## What is HuggingFace ?
------------
Hugging Face is a company that develops tools for building applications using machine learning. It is most notable for its transformers library built for natural language processing applications and its platform that allows users to share machine learning models and datasets.

## How to install chat_With_multiple PDFs
-------------------------------------
To install Chat_With_multiple_PDF follows the below step:
1. Clone the repository
2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```
3. Add the api key of huggingface and Openai.
4. run the command
   ```
   streamlit run app.py
   ```
