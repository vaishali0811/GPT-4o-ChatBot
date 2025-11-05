#GPT-4o Chatbot
An interactive AI chatbot built with Streamlit and OpenAI’s GPT-4o model.
This simple web app allows users to chat with GPT-4o in real time, just like ChatGPT — but customized and running locally or on the cloud

#Installation and Setup
openai==2.7.0
streamlit==1.51.0

#Install dependencies
pip install streamlit openai

#Create a config.json file
{
  "OPENAI_API_KEY": "your-api-key-here"
}

#Run the app
streamlit run main.py
