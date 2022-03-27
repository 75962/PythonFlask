installation:
    > py -3 -m venv venv
    > venv\Scripts\activate
    > pip install -r requirements.txt

start-up:
    > $env:FLASK_APP = "hello"
    > flask run
