# Multilinguistic-AI-Assistant

# How to run?
------------
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Vinit21592/Multilinguistic-AI-Assistant-GenAI.git
```

### STEP 01 - Create a conda environment after opening the repository

```bash
conda create -p venv python=3.8 -y
```

```bash
source activate venv/
```

### STEP 02 - Install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```

# Techstack Used
------------
- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s