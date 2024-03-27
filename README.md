#Medical Chat Bot using Machine Learning

#Medical Chat Bot (Meta Llama2)

Welcome to the Medical Chat Bot project! This end-to-end chat bot leverages machine learning to provide accurate medical information based on uploaded PDF medical data. Whether you’re a healthcare professional or a curious individual, this generative AI project aims to assist you with relevant responses.

##Features:
PDF Data Upload: Upload your medical data in PDF format.

Corresponding Results: Receive relevant and context-aware answers based on the uploaded data.

Generative AI: Powered by the Meta Llama2 model for natural language understanding.

Frontend/Web App: Built using Flask for a user-friendly interface.

Vector Database: Utilizes Pinecone for efficient storage and retrieval of embeddings


## Steps to run the project
```bash
conda create -n mchatbot python=3.8 -y
```

```bash
conda activate mchatbot
```

```bash
pip install -r requirement.txt
```

```bash
python app.py
```
 ```Access the chat bot at http://localhost:5000 in your web browser.```