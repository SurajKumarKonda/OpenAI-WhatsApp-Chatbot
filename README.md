# Creating a WhatsApp Chatbot integrated with ChatGPT, using Flask

## We have used:
- Ngrok and Flask as a server.
- Twilio as a WhatsApp agent.
- ChatGPT API for generating responses.
- Flask App as API for Request/Response model.
- AWS EC2 for deployment (24/7 running). 

## Steps
1. Create free account in [openai](https://platform.openai.com/account/api-keys), [Twilio](https://console.twilio.com/), [AWS](https://console.aws.amazon.com/), and [Ngrok](https://dashboard.ngrok.com/).
2. Open the Twilio console, and register your WhatsApp number. 
3. Create Flask App.
4. Launch EC2 in AWS.
5. Install requirements in EC2.
6. Setup credentials(OpenAI and Ngrok) in EC2.
7. Run Flask App in EC2.
8. Run Ngrok on same port as Flask App. 
9. Set up Ngrok URL in Whatsapp Sandbox (in Twilio console).
10. Done, chatbot is activated!!

## Usage:
- Open CMD in the working directory.
- Run the following command.

  ```
  pip install -r requirements.txt
  ```
- `BOT_API.py` is the Flask API that handles the Request/Response of ChatBot.
- To run this script follow this command.
  ``` 
    python3 BOT_API.py
