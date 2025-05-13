# 💬 Luminar Technolab Chatbot (Rasa + Flask)


A smart, intent-based chatbot built using Rasa 3.1 and Flask to assist users with inquiries about Luminar Technolab's courses, admissions, fees, and location.

## 🚀 Features

#### 🎯 Intent Recognition for key queries:
        
Courses offered

Admission process

Fee structure

Location and contact info
    
#### 🧠 Trained with 30+ examples per intent for high accuracy.
    
#### 📚 Rasa Core and NLU: Understands user queries and follows defined conversation paths.
    
#### 🌐 Flask Frontend: Simple local interface to interact with the bot.
    
#### 🧩 Modular code: Easy to expand and integrate with external tools or platforms.


## 📁 Project Structure

```

Rasa-chatbot-luminar/

├── data/                 # Contains training data: nlu.yml, rules.yml, stories.yml
├── domain.yml            # Intents, responses, actions defined here
├── config.yml            # NLU pipeline and policies
├── actions.py            # Custom action logic (if any)
├── app.py                # Flask web interface
├── .gitignore            # Ignores virtual environments, cache, etc.
└── README.md             # Project documentation
```

## ⚙️ Setup Instructions

1.Clone the repository:
```
git clone https://github.com/your-username/Rasa-chatbot-luminar.git
cd Rasa-chatbot-luminar
```
2.Create virtual environment and activate
```
python3 -m venv venv
source venv/bin/activate
```
3.Train the model:
```
rasa train
```
4.Run the Rasa server:
```
rasa run --enable-api
```
5.Run the Flask frontend (in a new terminal):
```
python app.py
```
## 📌 Use Cases
Student queries and lead generation

FAQ automation for Luminar Technolab

Can be extended for WhatsApp, Messenger, or web integration

## 🛠️ Future Improvements

Add dynamic content from CMS/database

Integrate with WhatsApp via Twilio

Deploy to cloud (e.g., Heroku, AWS, Railway)



