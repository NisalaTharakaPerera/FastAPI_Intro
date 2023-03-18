# FastAPI_Intro

![FastAPI Image](FastAPI.png)

This repository contains python scripts that I have made in the process of learning FastAPI.
Two youtube videos that I referenced are given below:

1. myapi.py     : https://www.youtube.com/watch?v=tLKKmouUams  
2. testapi.py   : https://www.youtube.com/watch?v=-ykeT6kk4bk

## Prerequisites

* You should have Python 3.7+ installed.
* Basic knowledge of Python helps.

## Steps

1. Install fastapi
Go to the terminal and type:

pip install fastapi


2. Install uvicorn
Uvicorn is an ASGI web server implementation for Python
To install type:

pip install uvicorn

3. After creating your python file (Eg: myapi.py, testapi.py), in the terminal go to the directory where your Python script is.

4. After that enter the following command:

uvicorn PYTHONSCRIPTNAME:FASTAPIVARIABLE --reload

Eg: uvicorn myapi:app --reload

* What reload does is that, it tells uvicorn to constantly reload the webserver everytime you make a change to the Python file storing the API.

5. You should see a message telling that "Application startup complete". 
It shows the URL that you need to go to access this website.

Eg: http://127.0.0.1:8000
