To set up and start the backend 

1. If not already existsing - create a virtual environment for your project:

     python3 -m venv venv

2.  On Windows: 

        venv\Scripts\activate

    On Unix or MacOS: 
    
        source venv/bin/activate

3. Install Flask and Transformers libraries in your virtual environment: 

     pip install flask transformers torch flask_cors

4. Execute fineTune.py

5. Run your Flask app:

Before running your Flask application, you need to set the FLASK_APP environment variable:

    On Windows:

        set FLASK_APP=app.py

    On Unix or MacOS:

        export FLASK_APP=app.py

6. Start your Flask application by running:

        flask run

Your API will be available at http://localhost:5000.
