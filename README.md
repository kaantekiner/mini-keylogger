# mini-keylogger
A simple keylogger, get key strokes and send it to related flask server. Written while training at SAU online class.
## Usage

Don't forget to change ip addresses and ports.

##### Starting Server
```
python3 server.py
```

##### Running Keylogger
```
python keylogger.py (win) 
python3 keylogger.py (*nix) 
```

##### .exe Convertion
```
#install helper tool, pyinstaller and run it

pip install pyinstaller

pyinstaller --onefile keylogger.py
```
There you have your .exe file.

While launch, the prompt remains foreground, will take care of it later.

Thats it...
