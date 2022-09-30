## Setup

The first thing to do is to create a virtual environment to install dependencies in and activate it:

```
$ python -m venv venv
$ .\venv\Scripts\activate.bat
```

Then install the dependencies:
```
(venv)$ pip install -r requirements.txt
```

Note the (venv) in front of the prompt. This indicates that this terminal session operates in a virtual environment set up by ``venv``.

Once pip has finished downloading the dependencies:
```
(venv)$ cd project
(venv)$ python manage.py runserver
```

And navigate to [http://127.0.0.1:8000/to_do/](http://127.0.0.1:8000/to_do/).