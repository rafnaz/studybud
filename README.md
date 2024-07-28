https://user-images.githubusercontent.com/72341453/134747028-7e2d90cc-a92f-4f66-815e-54a0d50cca54.PNG
StudyBuddy

Cloning the repository
--> Clone the repository using the command below :

git clone https://github.com/divanov11/StudyBud.git
--> Move into the directory where we have the project files :

cd StudyBud
--> Create a virtual environment :

# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname
--> Activate the virtual environment :

envname\scripts\activate
--> Install the requirements :

pip install -r requirements.txt
Running the App
--> To run the App, we use :

python manage.py runserver
⚠ Then, the development server will be started at http://127.0.0.1:8000/
