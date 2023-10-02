1.1 create a virtual environment named .venv based on your current interpreter:
```
    # Linux
    sudo apt-get install python3-venv    # If needed
    python3 -m venv .venv
    source .venv/bin/activate

    # macOS
    python3 -m venv .venv
    source .venv/bin/activate

    # Windows
    py -3 -m venv .venv
    .venv\scripts\activate
```

1.2 Activate virtual environment:
   ```
    .venv\Scripts\Activate 
   ```

## install requirements
```
pip install -r requirements.txt
```

## Migrate 
```
python3 manage.py makemigrations
python3 manage.py migrate
```