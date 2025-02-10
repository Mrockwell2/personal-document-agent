# personal-document-agent

A personalized chat bot agent to answer questions about your uploaded document.

Deployed version of the app [Click Here](https://chat-with-document.streamlit.app/)

How to run this project ?

### Setup

1. Run `pip install -r requirements.txt`
2. Run `streamlit run ./chat_with_documents.py`

### Approach #1: 

1. Add .env file after you clone this project.
2. Paste the below code and add the values for your APIs

```sh
AWS_ACCOUNT_ID=""
AWS_ACCESS_KEY_ID=""
AWS_SECRET_ACCESS_KEY=""
PINECONE_API_KEY=""
PINECONE_ENV=""
```

3. Run `pip install -r requirements.txt`
4. Finally run `streamlit run ./chat_with_documents.py`

N.B. Make sure AWS is configured on your machine (run `aws configure`) 

### Approach #2

1. You can run the project and make sure to paste the Open Api key (as shown below)

### Learning Resources
- This was created with the help of ZTM's project tutorial. Check them out at [ZeroToMastery.io](https://academy.zerotomastery.io/)
- I have added **learning-resources** folder to this repo
