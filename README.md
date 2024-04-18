Create a .env file and add a OPENAI_API_KEY as

OPENAI_API_KEY = "sk-" // your key

Steps to install:

Step 1: Clone the repo to your specified folder.
    git clone https://github.com/RAVITEJA9121/Rag-Django.git

Step 2: change directory to the Rag
    cd Rag

Step 3: Create the virtual environment.
    python -m venv .venv

Step 4: Activate the environment.
    i) mac: source .venv/bin
    ii) windows: cd .venv/Scripts
        >> activate
        >> cd ..
        >> cd ..

Step 5: Install all the requirements using python.
    python -m pip install -r requirements.txt

Step 6: Change your directory to the Rag project.
    cd Rag

Step 7: Run the django-server
    python manage.py runserver


