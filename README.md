<h1>Covid-O-Win-Hospital-Management</h1>

<h2>Aim</h2><br>
This site is basically created in order to help hospital manage the beds and seeking pharmacy helps during emergency.
<br>
<h2>Features of the Site</h2><br>
+ Add Beds.<br>
+ Manage Beds.<br>
+ Login as admin.<br>
+ Nearby Hospitals Feature.<br>

<h2>Deployed Link</h2>
<h3>Link - <a href="https://covidowin.pythonanywhere.com/">[https://covidowin.pythonanywhere.com/]</a></h3>

<h2>Walkthrough Video</h2>
<h3>Link - <a href="https://drive.google.com/file/d/1CiE_ikIGSbU8BMdU59NJScSvPLIb9d-t/view?usp=sharing">[Watch Video]</a></h3>


Do this to make Covid-O-Win run :
<br>
1. First install requirements.txt <br>
pip install -r requirements.txt


2. Then do Database migrations : <br>
python manage.py makemigrations<br>
python manage.py migrate<br>

3. You need to runserver :<br>
python manage.py runserver<br>

4. If you want to createsuperuser : <br>
python manage.py createsuperuser<br>
