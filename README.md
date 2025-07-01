# 🩺 Doctor Bot – Heart Disease Chatbot
Doctor Bot is a simple conversational chatbot that answers user queries about heart disease by processing medical article content. It uses Natural Language Processing (NLP) techniques to analyze questions and respond with relevant information.

# 🧠 Features
🤖 Greets users politely and responds to greetings
📚 Parses and extracts information from a medical article (via newspaper3k)
🗣️ Answers user queries using similarity matching
🧠 NLP techniques: sentence tokenization, cosine similarity, and vectorization
🎨 Colored user/bot responses for readability (in Colab/terminal)
🔁 Continues the conversation until the user exits

# 🛠️ Technologies Used
Python 3
newspaper3k – article scraping and parsing
nltk – text tokenization and processing
scikit-learn – vectorization and cosine similarity
ANSI color codes – colored console output
Google Colab – for interactive development

## 📄 Sample Source Article
Doctor Bot fetches data from this article:
🔗https://www.mayoclinic.org/diseases-conditions/heart-disease/symptoms-causes/syc-20353118 Mayo Clinic - Heart Disease

## 🧪 Example Conversation
You: hi  
Doc Bot: hello

You: what is heart disease  
Doc Bot: Heart disease refers to several types of heart conditions, including...

You: what are the symptoms  
Doc Bot: Chest pain, shortness of breath, fatigue, and irregular heartbeat...

You: bye  
Doc Bot: Get back with you later!!


# 🚀 How to Run
Clone the repo:

bash
```
git clone https://github.com/your-username/doctor-bot.git
cd doctor-bot
```

# Install dependencies:

bash
```
pip install newspaper3k scikit-learn nltk
```

# Run the bot:

bash
```
python doctor_bot.py
```

✅ Works well in Google Colab with color support.
