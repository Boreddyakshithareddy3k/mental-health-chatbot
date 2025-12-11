Mental Health Chatbot

An empathetic AI assistant built with Python and Streamlit to support mental-health conversations through emotion-aware responses and safe interaction practices. This project includes added safety features and a reproducible evaluation system.

🔒 Safety & Ethics

Added a dedicated Safety & Ethics document (SAFETY.md) describing crisis detection, emergency helplines, ethical boundaries, and responsible use.

Includes clear disclaimers that the chatbot is not medical advice or a therapeutic replacement.

Crisis-related phrases trigger safe escalation messages.

📊 Evaluation Workflow

A simple evaluation pipeline was added under evaluation/ to measure:

Helpfulness (human-rated, 1–5 scale)

Safety recall & precision for crisis detection

To run evaluation:

python evaluation/metrics.py


This provides reproducible metrics for assessing conversational quality and safety.

▶️ Running the Chatbot
pip install -r requirements.txt
streamlit run src/app/app.py

📁 Project Structure
├── src/                 # App code
├── SAFETY.md            # Safety & ethics documentation
├── evaluation/          # Helpfulness & safety evaluation
└── README.md
