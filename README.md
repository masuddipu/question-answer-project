# QUORA LIKE QA APP

**A Quora-like Single Page Application built with Django, Django REST Framework and Vue JS**

This is an intermediate/advanced level project, therefore knowledge of Python, Django, HTML, CSS and JavaScript is assumed.


### Hot to set up the project to run on your local machine?
*****
#### 1. Download the code to your PC and move inside the folder.
#### 2. Create a new Python Virtual Environment(Windows):
``` 
pip install pipenv 
pipenv shell
pip install -r requirements.txt
```
#### 3. Apply the migrations as usual.
```
python manage.py makemigrations
python manage.py migrate
```

#### 4. Install the Vue JS dependencies:
```
cd project_folder/frontend
npm install
```

#### 4. Run Vue JS Development Server:
```
npm run serve
```

#### 5. Run Django's development server:
```
python manage.py runserver
```
****
#### Open up Chrome and go to 127.0.0.1:8000 and the app is now running in development mode!
*****
## Happy coding!