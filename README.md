# Flask blog website

## Setup

### Dependancies

- Python 3.6.9 / Flask 3.0

The following steps will walk you thru installation on a Mac. Linux should be similar.
It's also possible to develop on a Windows machine, but I have not documented the steps.
If you've developed the blog flask apps on Windows, you should have little problem getting
up and running.

### Installing Geospatial libraries

On Mac
```
$ brew install flask
```

On Debian/Ubuntu Linux
```
$ sudo pip install flask
```

### Create virtualenv

On Mac
```
$ sudo python2 Downloads/get-pip.py
$ sudo python2 -m pip install virtualenv
```

Debian, Ubuntu
```
$ sudo apt-get install python-virtualenv
```

```
$ virtualenv venv --python=python3.7
```

Then active virtualenv
```
source venv/bin/activate
```

