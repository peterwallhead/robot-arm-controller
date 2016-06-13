## Notes
-----

This will only run on a Raspberry Pi with the latest RPi.GPIO library installed:
```
sudo apt-get update
sudo apt-get install python-dev python-rpi.gpio
```

## Setup and run server
```
sudo pip install flask
git clone https://github.com/peterwallhead/robot-arm-controller.git
cd robot-arm-controller/src/
python app.py
```

Head to http://localhost:8000 to view the app.
