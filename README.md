# Medical Chat Bot using Machine Learning

## Medical Chat Bot (Meta Llama2)

Welcome to the Medical Chat Bot project! This end-to-end chat bot leverages machine learning to provide accurate medical information based on uploaded PDF medical data. Whether you’re a healthcare professional or a curious individual, this generative AI project aims to assist you with relevant responses.

## Features:

PDF Data Upload: Upload your medical data in PDF format.

Corresponding Results: Receive relevant and context-aware answers based on the uploaded data.

Generative AI: Powered by the Meta Llama2 model for natural language understanding.

Frontend/Web App: Built using Flask for a user-friendly interface.

Vector Database: Utilizes Pinecone for efficient storage and retrieval of embeddings


## Steps to run the project:

### Clone the repository

Project repo: https://github.com/

### STEP 01- Create a conda environment after opening the repository

conda create -n mchatbot python=3.8 -y
conda activate mchatbot
### STEP 02- install the requirements

pip install -r requirements.txt

### Create a .env file in the root directory and add your Pinecone credentials as follows:
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

### Download the quantize model from the link provided in model folder & keep the model in the model directory:
### Download the Llama 2 Model:
llama-2-7b-chat.ggmlv3.q4_0.bin

### From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

### run the following command
python store_index.py

### Finally run the following command
python app.py

Now,open up localhost:


## Usage:

Upload your PDF data.

Ask questions related to your data or any other related topic.

Receive context-aware responses generated by the Meta Llama2 model.


## License:

This project is licensed under the MIT License - see the LICENSE file for details.