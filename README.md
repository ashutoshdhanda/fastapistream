# fastapistream
Bare minimun FastAPI to display webcam stream in browser.

$pip install fastapi


$pip install uvicorn

python myapp.py

or

uvicorn myapp:app

or

You can specify additional parameters such as:

    reload: Enable auto-reloading which will refresh the server when you made modification to the file. Extremely useful for local development.
    port: Port number for the server. Default is 8000.

The following example will use 5000 as the port number.

uvicorn myapp:app --reload --port 5000
