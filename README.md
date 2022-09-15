                             # Django-Web-App
I created this project as a Demo for my internship. It is a basic web application developed using Django.<br >
The app is still under development but I will keep on updating it.<br> 
It runs entirely on python, even the login and registration forms are built using python.


##  Installing
### Open terminal and Clone this repo<br/>
    git clone https://github.com/brianblue05/Django-Web-App.git
### Navigate into the dir with manage.py  (`Bree` dir) <br><br/>
    cd Django-Web-App/Bree
### Install the requirements. Ignore any arrors from this code<br/>
    pip install -r requirements.txt
### Migrate the database using (python or py may work instead of python3): <br/>
    python3 manage.py makemigrations
    python3 manage.py migrate
### Create a superuser (optional) to login into http://127.0.0.1:8000/admin <br/>
    python3 manage.py createsuperuser
### To run the program in local server use <br/>
    python3 manage.py runserver
### Then go to http://127.0.0.1:8000 in your browser <br/>

### Click on Register and add a new user, then log in.
