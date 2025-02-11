# healthcare_ai_chatbot
# HealthCare Assistant ChatBot

## Introduction
The **HealthCare Assistant ChatBot** is an AI-powered conversational agent designed to assist users with healthcare-related queries. Developed using Hugging Face’s OpenAI Community Edition GPT-2, this chatbot provides symptom guidance, appointment scheduling assistance, and general healthcare information.

## Features
- **Symptom Analysis**: Provides initial guidance if a user mentions symptoms and advises consulting a doctor.
- **Appointment Scheduling Assistance**: Helps users inquire about and proceed with booking medical consultations.
- **Medication Guidance**: Reminds users about prescribed medicines and encourages consulting their doctor.
- **General Healthcare Queries**: Utilizes GPT-2 text generation to respond to various healthcare-related questions.

## How It Works
1. **Hugging Face Transformers Pipeline**: Uses GPT-2 to generate responses.
2. **NLTK (Natural Language Toolkit)**: Tokenizes words and manages stopwords.
3. **Category Matching**: Identifies user input type (symptoms, appointments, medication, or general queries).
4. **Streamlit Integration**: Provides a user-friendly interface for interaction.

## Installation & Setup
### Prerequisites
- Python (>=3.7)
- pip
- Virtual environment (optional but recommended)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/healthcare-chatbot.git
   cd healthcare-chatbot
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Chatbot**
   ```bash
   streamlit run app.py
   ```

## Limitations
- Does **not** replace professional medical advice.
- AI-generated responses may **not always be accurate**.
- Users should consult a certified medical professional for serious concerns.

## Future Enhancements
- **Integration with a medical knowledge base** for better accuracy.
- **Speech-to-Text and Text-to-Speech features** for better interaction.
- **Multi-language support** to reach a broader audience.

## License
This project is licensed under the **MIT License**.

---

