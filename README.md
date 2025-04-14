# ML-CLI Assistant 🔊🧠

##🚀 A Machine Learning-powered smart, extensible Python assistant that supports following  Features:

- 🤖 Intent classification and prediction using `scikit-learn`
- 📊 System stats
- 🎤 Speech input and Speech recognition (`speech_recognition`)
-🎙  NLP (HuggingFace)
- 🌐 Web & YouTube search
- 🎵 Music player & Music directory access
- 📧 Email sending via SMTP
- 🌦 ☁️ Weather info (OpenWeatherMap API)- 📊 System stats display
- 🖥 PyQt5 GUI with toggle interface
- 🧰 CLI support via argparse or Typer


# Github repository structure
ml_cli_assistant/
├── ml_cli_assistant/
│   ├── __init__.py
│   ├── assistant.py         # Main logic
│   ├── model.pkl            # Saved intent model
│   ├── speech_utils.py      # Speech recognition helper
│   └── nlp_utils.py         # HuggingFace NLP (optional)
├── setup.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore


# Tools You’ll Likely Need:
	•Python, OpenCV, PyTorch, Flask, Docker, Celery, Redis, Raspberry Pi, NodeMCU, MQTT, psutil, Pandas, Scikit-learn


## 📦 Installation
```bash

# Creating a Virtual python environment inside a project folder and installing required dependencies ml_cli_assistant

cd ml_cli_assistant
python3 -m venv venv
source venv/bin/activate
pip install transformers torch scikit-learn spacy requests psutil

git clone https://github.com/<sharvinsoham>/ml_cli_assistant.git
cd ml_cli_assistant
pip install .
mlcli


## 🚧 3. Upcoming Upgrades
### 🔲 HuggingFace NLP (`nlp_utils.py`)
- `transformers` + `pipeline('zero-shot-classification')` for more dynamic intent prediction.

### 🖼️ Desktop GUI
- PyQt5: Modern, native-looking app.
- Tkinter: Simple, light GUI for beginners.
