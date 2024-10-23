- Create virtual env `python -m venv venv` then run `venv\Scripts\activate` to activate the environment.
- Install dependencies `pip install -r requirements.txt`.
- Run server `streamlit run app.py`. Then go to default URL http://localhost:8501
- Add your desired model name you want the app to process with, default currently is ollama - llama3.2

-- If Error occurs

PermissionError: [WinError 10013] An attempt was made to access a socket in a way forbidden by its access permissions

Run Command in Admin Mode

- net stop winnat
- net start winnat

Reference: https://youtu.be/YqqRkuizNN4?si=0aj27Jo03pIeP6bY