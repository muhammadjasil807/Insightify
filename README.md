Insightify AI/ML NLP Powered Text & Mental Health Insights

**Insightify** is an AI/ML NLP powered text analyzer that provides **Sentiment, Intent, Emotion, Named Entities, Toxicity, Mental Health Insights, Emotional Safety Detection, and Supportive Responses** based on user input. The system leverages transformer-based models and SpaCy NLP pipelines to understand text and detect mental health cues such as stress, sadness, excitement, happiness, and emotional risk signals.

Deployed via **Streamlit**, it provides a real time, interactive interface for text analysis and compassionate support.

---

## Overview

This project demonstrates an end-to-end AI/ML pipeline for analyzing text sentiment, emotion, intent, entities, toxicity, mental health cues, and emotional safety. Users can input any text, and Insightify predicts:

* **Sentiment:** Positive or Negative
* **Intent:** Greeting, Complaint, Question, or Statement
* **Emotions:** Joy, Sadness, Anger, Surprise, etc.
* **Named Entities:** Person, Product, Organization, Location, etc.
* **Toxicity:** Low, Moderate, High
* **Mental Health Insights:** Stress, Anxiety, Excitement, Depression cues
* **Emotional Safety Detection:** Flags emotional risk or indicates emotional safety
* **Supportive Response:** Provides empathetic and encouraging responses

**Example Inputs & Outputs:**

**Input:**
“Why is my phone not working again? This is so frustrating.”
**Output:**

* Sentiment: Negative
* Intent: Complaint
* Emotion: Anger, Sadness, Surprise
* Named Entities: phone (PRODUCT)
* Toxicity: Low
* Mental Health Insight: Disappointment / Sadness
* Emotional Safety Detection:  Seems Emotionally Safe
* Supportive Response: "It's natural to feel frustrated. Take a moment to relax and let out your feelings safely."

**Input:**
“I feel like nothing in my life is going right.”
**Output:**

* Sentiment: Negative
* Intent: Statement
* Emotion: Sadness
* Named Entities: None
* Toxicity: Low
* Mental Health Insight: Disappointment / Sadness
* Emotional Safety Detection:  Seems Emotionally Safe
* Supportive Response: "I'm here for you. Sharing how you feel is brave, and it's okay to feel this way. You're not alone."

**Input:**
“I am feeling excited about my new project!”
**Output:**

* Sentiment: Positive
* Intent: Statement
* Emotion: Joy, Excitement
* Named Entities: None
* Toxicity: Low
* Mental Health Insight: Excitement / Happiness
* Emotional Safety Detection: Seems Emotionally Safe
* Supportive Response: "Thank you for sharing. Remember, it's okay to express your emotions. You're heard."

 Features

* Interactive **Streamlit web interface**
* Real-time **sentiment, intent, emotion, entity, toxicity analysis**
* **Mental health insights** using detected emotions and keywords
* **Emotional Safety Detection** to flag potential risk in user input
* **Supportive Response Generator** providing empathetic and encouraging messages
* Transformer-based models for **accurate emotion detection**
* SpaCy NER for **Named Entity Recognition**
* Toxicity detection for **safer content analysis**
* Easy deployment via **Streamlit**

 Tech Stack

* **Programming Language:** Python 3
* **AI / ML Models:** Hugging Face Transformers (Sentiment, Emotion, Toxicity)
* **NLP / NER:** SpaCy (en_core_web_trf / fallback en_core_web_sm)
* **Frontend / UI:** Streamlit
* **Deployment:** Streamlit + Pyngrok (optional for public URL)
* **Model Saving / Loading:** Hugging Face Transformers, PyTorch

Project Structure

```
insightify
│
├── app.py                   # Streamlit web app
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
├── .gitignore               # Ignored files
└── models/                  # Folder for saving models (optional)
```

 Installation and Running

**Step 1** - Clone the Repository
**Step 2** - Install Dependencies
**Step 3** - Run the Streamlit App
**Step 4** - (Optional) Public URL via Ngrok

 Future Improvements

* Add **detection for depression, phobia, anxiety severity**
* Include **multi-language support**
* Deploy on **Streamlit Cloud or Hugging Face Spaces**
* Save **user history** for trend analysis
* Add **visualization for emotion trends over time**
* Improve **supportive response AI** with contextual understanding

 Conclusion

This project demonstrates how AI and NLP can provide actionable insights into text, emotional state, and mental health cues. It’s a foundation for building more advanced **mental health and text analysis tools** that are **empathetic, interactive, and safe**.

