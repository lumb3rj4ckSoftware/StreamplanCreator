# Requirements
```
flask==3.0.3
flask-socketio==5.3.6
python-socketio==5.11.4
python-engineio==4.9.0
```

# CFG Ablegen Windows
```
...\Counter-Strike Global Offensive\game\csgo\cfg\gamestate_integration_killstreak.cfg
```

# Vorbereiten
```
python -m venv .venv

# Windows:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

.venv\Scripts\activate


# Linux/macOS:
source .venv/bin/activate

pip install -r requirements.txt

```

# Starten
```
# Windows:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

.venv\Scripts\activate

# Linux/macOS:
source .venv/bin/activate

python app.py

```

# Testen
```
# Windows:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

.venv\Scripts\activate

# Linux/macOS:
source .venv/bin/activate

python app.py --test

```
