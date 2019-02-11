# todo-api

This is an application I am using to learn how to write a Python API using flask.
The learning example is credited to: https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask

## Setup

1. Install Chocolatey (Windows Package Manager) 
    * [Documentation for Chocolatey](https://chocolatey.org/)
    * ```Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))```
1. Install python3 via chocolatey
    * ```choco install python```
1. Install virtualenv via pip (python package manager similar to npm)
    * [pip documentation](https://pypi.org/project/pip/)
    * ```pip install virtualenv```
1. Create a virtual environment for flask via virtualenv inside the repo you wish to make a virtual environment for
    1. ```virtualenv flask```
    1. ```pip install flask```

## How to run

1. From within the repository simply type:
    * ```python app.py```
    * The app should be running at: ```http://127.0.0.1:5000/``` by default
