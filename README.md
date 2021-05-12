Django-translation is one of the cool feature that most of the website use for better UI experience.
Here this project involves a simple login page which support both english and nepali translation.
we make use of i18n which is on by default in django along with gettext gnu for perfoming translation.


## Quick Start
1.Clone repo like this:
 ```sh
 git clone https://github.com/Aasess/Django-MultiLanguage-Translation-i18n.git
```


2.Create a virtualenv in cmd
```sh
python3 -m venv virtualenv
```


3.Activate virtualenv in cmd
```sh
virtualenv\Scripts\activate.bat
```



4.Install packages from requirements.txt file
```sh 
pip install -r /path/to/requirements.txt
```


5.Run migrations as:
```sh 
python manage.py makemigrations
python manage.py migrate
```


6.Start the development:
```sh
python manage.py runserver
```
7.visit http://127.0.0.1:8000/


## Handling Frontend Template

 Import [```bootstrap-select```](https://developer.snapappointments.com/bootstrap-select/) css and js cdn and read the necessary documentation.

This is to make our ```select``` and ```option``` tags beautiful and add flags icon to the ```select``` tags.


## Handling Backend

