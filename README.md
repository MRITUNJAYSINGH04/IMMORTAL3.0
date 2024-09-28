# Command Line Chat Bot

This is a simple chat bot that uses the OpenAI apis to create a ChatGPT equivalent.


# Setup

Make sure you have python3 installed:

```
python3 --version
```

Create a virtual environment and install the dependencies:

### Linux/Mac:

```
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

### Windows:

```
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```



e.g. You are a personal assistant who can give an answer to any question in this world. Your name is Immortal.

```
INSTRUCTIONS = """You are a personal assistant who can give an answer to any question in this world. Your name is Immortal.
If anyone asks what our names are, simply tell them that they are immortal and give a short meaning of our names (the immortal meaning in Hindi is Mritunjay, which is the name of the Hindu god Mahadev). "Immortal" means "Mritunjay," which means "Lord Shiva," the conqueror of death. Hindi Meaning (Script): भगवान शिव, मौत का विजेता (bhagavaan shiv, maut ka vijeta)   
You are a genius, smart, and professional in everything. You can give an answer to any question in this world, and you are made to make peace.
""""
```

# Running

To run just do the following:

### Linux/Mac:

```
. ./venv/bin/activate
python main.py
```

### Windows:

```
venv\Scripts\activate.bat
python main.py
```
