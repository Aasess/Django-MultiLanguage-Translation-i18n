Django-translation is one of the cool feature that most of the website use for better UI experience.
Here this project involves a simple login page which support both english and nepali translation.
we make use of i18n which is on by default in django along with gettext gnu for perfoming translation.


# Quick Start
1.Clone repo like this:
 <pre>git clone https://github.com/Aasess/Django-MultiLanguage-Translation-i18n.git</pre>

2.Create a virtualenv in cmd
<pre>python3 -m venv virtualenv</pre>

3.Activate virtualenv in cmd
<pre>virtualenv\Scripts\activate.bat</pre>

4.Install packages from requirements.txt file
<pre>pip install -r /path/to/requirements.txt</pre>


5.Run migrations as:
<pre>python manage.py makemigrations
python manage.py migrate</pre>

6.Start the development:
<pre>python manage.py runserver</pre>

7.visit http://127.0.0.1:8000/


# Handling frontend template

 Import "bootstrap-select css and js cdn" and read the necessary documentation : https://developer.snapappointments.com/bootstrap-select/

This is to make our <pre>select</pre> and <pre>option</pre> tags beautiful and add flags icon to the <pre>select tags</pre>


# Handling backend

