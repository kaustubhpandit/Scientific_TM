<p align="left">
  <img src="https://github.com/kaustubhpandit/ETHelper/blob/main/images/page_icon.png" width="60" height="60" alt="ET Helper Logo" style="float:left; margin-right:10px;" />
  <h1 style="padding-top:15px;">ET Helper</h1>
</p>



ET Helper is a Streamlit-based web application designed to facilitate the interactive querying of text extracted from PDF files. It leverages advanced NLP models from OpenAI, embedded via the LangChain library, to provide a conversational interface where users can upload PDFs and ask questions directly related to the content.

## Features

- PDF text extraction using PyPDF2.
- Conversational interface powered by OpenAI models.
- Real-time response to queries based on uploaded document content.
- Vector storage using FAISS to optimize retrieval of information.

## Prerequisites

Before you begin installation, ensure you have Python 3.8+ installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

## Installation

Follow these steps to get ET Helper up and running on your local machine:

### 1. Clone the repository

Clone the ET Helper repository to your local machine using the following command:
```bash
git clone [https://github.com/kaustubhpandit/ETHelpery]()
```

### 2. Install required dependencies

Install the required Python libraries specified in `lib_req.txt`:
```bash
pip install -r lib_req.txt
```

### 3. Set up the environment

Paste your OpenAI API key in the `.env` file in the project directory. You can obtain an API key by signing up at [OpenAI](https://openai.com/):

```
OPENAI_API_KEY="ENTER YOUR API KEY"
```

## Usage

To use ET Helper, follow these simple steps:

### 1. Start the Application

Run the application using the Streamlit command:
```bash
streamlit run et_helper.py
```
This command will start the server and open the application in your default web browser.

### 2. Upload PDF Documents

Once the application is running, you'll see an option to upload PDF files. Use the file uploader to select the PDF documents from which you wish to extract and query text.

### 3. Query the Documents

After uploading the documents, you can type your questions in the chat interface provided. The system will process your query against the content of the uploaded PDFs and return relevant responses.

## Contributing
Contributions to ET Helper are welcome! Please feel free to fork the repository, make changes, and submit pull requests. You can also open issues if you find bugs or have suggestions for improvements.


