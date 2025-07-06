# 🧠 Indian Budget Chatbot (RAG-based)

This project presents a set of intelligent chatbot applications that leverage a Retrieval-Augmented Generation (RAG) model trained on the Indian Budget Speech PDF (budget_speech.pdf). The goal is to enable users to interact with the budget data via text, voice, and multilingual support.

## 📁 Project Structure

**streamlit_app.py – Indian Budget Text Chatbot**

- A simple and interactive chatbot built with Streamlit:

    - Uses a RAG model trained on budget_speech.pdf.

    - Users can type questions related to the Indian budget.

    - The chatbot returns accurate responses in text format.

**streamlit_app_voice.py – Indian Budget Voice Chatbot**           88

- An enhanced chatbot version with voice input and output:

    - Same RAG model trained on budget_speech.pdf.

    - Users can either type or speak their questions.

    - The chatbot returns responses in both text and voice formats.

**streamlit_app_translator.py – Indian Budget Voice Chatbot with Translation**

- A multilingual voice chatbot supporting regional languages:

    - Accepts typed or spoken questions in any language (e.g., Marathi).

    - Utilizes translation tools alongside the RAG model.

    - Returns the response in text and voice in the same language used by the user.

**💡 Features**

- 📄 Understands complex budget content through RAG.

- 🎙️ Voice input and output.

- 🌍 Multilingual support for broader accessibility.

- 🧩 Modular and built with Streamlit for easy deployment.

**📦 Requirements**

- Make sure to install the following dependencies before running the apps:

pip install langchain-cli
pip install langchain
pip install langchain-community
pip install langchain-google-genai
pip install google-generativeai
pip install langchain-pinecone
pip install pypdf
pip install python-dotenv
pip install speechrecognition
pip install pydub
pip install gtts
pip install pyaudio
pip install deep-translator
pip install streamlit

**🚀 Future Enhancements**

- Integration with real-time budget updates.

- Language selection dropdown for ease of use.

- Visual summaries using charts and graphs.
