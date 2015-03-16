# zephyros-stats
live-updating statistics for a raspberry pi

This is a proof-of-concept project to verify that Flask + Flask-SocketIO can be used to make a live-updating web page that communicates with a Raspberry Pi.

To make it work:
- Make sure you have python 2 installed.
- Install a python 2 versions of Flask and Flask-SocketIO. You may want to [use a virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) to do so.
- Run `app.py` in python 2. If you want to run it on port 80, you may need to run it with root permissions.
