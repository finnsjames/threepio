# Threepio 🤖

This repo includes data for the data acquisition system for the 40-foot radio telescope at the [Green Bank Observatory](https://greenbankobservatory.org/). This software is part of the [ERIRA](https://www.danreichart.com/erira) program. The DAQ itself is the Python application **Threepio**, in the subdirectory of the same name; the other directories include relevant data and information from the larger instrumentation upgrade project.

## Dependencies

**Threepio** uses `PyQt5` for GUI and `pySerial` for communication to the data collection hardware (DataQ).

## Setting Up

Clone the repo and `cd` into it.
```
$ git clone https://github.com/radiolevity/threepio.git
$ cd threepio
```

**Threepio** requires Python 3.7; we strongly recommend using a virtual environment.
```
$ python -m venv env
```

Activate the virtual environment.
```
$ source ./env/bin/activate
```

Check that the python version is correct (any 3.7.x is fine).
```
$ python --version
Python 3.7.10
```

Install dependencies. You may need to update pip.
```
$ pip install -r requirements.txt
```

Run
```
$ python threepio.py
```
