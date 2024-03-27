# MobilyAR-PDF-Chatbot

Overview
--------

The PDF Chatbot project aims to create a conversational agent using machine learning frameworks that can interact with PDF documents. This cutting-edge application enables users to easily search and retrieve information from PDF files using natural language, thus making the data more accessible and user-friendly.

Getting Started
---------------

Dependencies
------------

Operating System:  This program is compatible with various operating systems including Windows.

Prerequisites:

-   Python 3.10

-   Pip (Python package manager)

Libraries:

-   LangChain: A prerequisite library for leveraging LLama and Mistral 7B models within the LangChain framework.

-   Torch: The PyTorch library is required for deep learning functionalities.

-   Sentence Transformers: This library provides implementations of various sentence embedding models.

-   Faiss-CPU: A library for efficient similarity search and clustering of dense vectors.

-   Hugging Face Hub: Required for accessing pre-trained models and related resources.

-   PyPDF: Used for parsing PDF documents and extracting text.

-   Accelerate: Provides acceleration utilities for PyTorch training and inference.

-   LLama-CPP-Python: Facilitates integration with the LLama model for advanced natural language processing tasks.

-   Transformers: The Hugging Face Transformers library implements popular NLP models and utilities.

### Installing

Instructions for Installing and Running the Program:

-   Download the Project:

-   Clone the project from the GitHub repository.

-   You can also download the Zip file from Github and Extract the contents of the zip file to a directory of your choice.

-   Create and Activate Virtual Environment:

-   Navigate to the directory where you extracted the project files.

-   Open a terminal or command prompt in that directory.

-   Create a virtual environment with Python version 3.10 using the following command:

"python3.10 -m venv venv"

-   Activate the virtual environment:

On Windows:venv\Scripts\activate

On Linux use: source venv\bin\activate

-   Install Dependencies:

-   After activating the virtual environment, Find and open the .ipynb file in VSCode.

-   Install the Python Kernal Package and check the connection is proper.

-   Run the first cell in the .ipynb script to install all dependencies.

-   Upload PDF File:

-   Place the PDF file that you want to analyze in the data folder within the project directory.

-   Upload Model:

-   Download the mistral-7b-instruct-v0.1.Q4_K_M.gguf model.

-   [mistral-7b-instruct-v0.1.Q4_K_M.gguf ](https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF/blob/main/mistral-7b-instruct-v0.1.Q4_K_M.gguf)

-   Ensure that you have the correct version and format of the model for compatibility with the program.

-   Place Model in Models Folder: Once downloaded, move the mistral-7b-instruct-v0.1.Q4_K_M.gguf model file to the model folder within the project directory.

### Executing program

To run the .ipynb file in VS Code and execute all cells one by one, follow these steps:

-   Open VS Code:

-   Launch Visual Studio Code on your local machine.

-   Open Notebook File:

-   Open the .ipynb notebook file within VS Code.

-   Select Kernel:

-   Make sure to choose the correct kernel for the notebook, which should have the same virtual environment name.

-   Navigate to the top-right corner of the notebook window, where you'll see the kernel name. Click on it and select the desired kernel. For Python notebooks, you would typically choose a Python kernel.

-   Run Cells:

-   To execute all cells one by one, you can use the "Run Cell" option.

-   Click on the first cell to select it.

-   Then, either press Shift + Enter or click on the "Run Cell" button in the toolbar at the top of the notebook.

-   This will execute the current cell, and the focus will move to the next cell.

-   Continue executing cells sequentially until you have run all the cells in the notebook.

-   Monitor Execution:

-   As you run each cell, monitor the output and any prompts or instructions provided in the notebook.

-   Follow the instructions for interacting with the chatbot and analyzing the PDF document.

-   Review Results:

-   Once you have executed all cells, review the results displayed in the notebook output.

-   Interact with the chatbot as instructed and analyze the PDF document as required.
