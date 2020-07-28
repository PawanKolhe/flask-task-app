# Flask Task app

## Requirements

- Python 3

## Environment Setup
> NOTE:  Python 3 maybe installed as `python` or `python3` in your system. Same applies for `pip` / `pip3`.

1. Install `vitualenv` for isolated Python environment  
```bash
pip3 install virtualenv
```

2. Create `vitualenv` named env
```bash
virtualenv env
```

3. Launch `virtualenv`

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
  
4. Install Dependencies  
```bash
pip3 install -r requirements.txt
```

5. Start server
```
python3 app.py
```

6. Open `http://127.0.0.1:5000` in browser

