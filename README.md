# Flask Task app

## Requirements

- Python 3

## Environment Setup

1. Install `vitualenv` for isolated Python environment  
```bash
pip3 install virtualenv
```

2. Launch `virtualenv`

- **Windows**
  ```powershell
  # Powershell
  .\env\Scripts\activate.ps1

  # CMD
  .\env\Scripts\activate.bat
  ```
- **Linux**
  ```bash
  source ./env/Scripts/activate
  ```
  
3. Install Dependencies  
```bash
pip3 install -r requirements.txt
```

4. Start server
```
python3 app.py
```

4. Open `http://127.0.0.1:5000` in browser
