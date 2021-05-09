# Eventima
EvenTima is an event management django based webapp. Due to COVID-19 our new normal life is shifted to the virtual world of the internet. In this scenario it is very difficult to organize and manage an event. There does not exist any well structured event management system for the schools and universities which can help in managing the events smoothly in which they can manage all the events, the team members of the event and people who are participating in that event. Thus, it is the need of the hour to propose an event management system that can fulfill these requirements. Our project Eventima is a step in this way.

# How To Setup On Windows
<b>1. Clone This Project:</b> git clone https://github.com/SouravSehgal-3009/Eventima.git<br>
<b>2. Go to Project Directory:</b>  cd Eventima<br>
<b>3. Create a Virtual Environment:</b>  python -m venv eventima_env<br>
<b>4. Activate Virtual Environment:</b> eventima_env\Scripts\activate.bat<br>
<b>5. Install Requirements Package:</b> pip install -r requirements.txt<br>
<b>6. Migrate Database:</b> python manage.py migrate<br><br>
If you get an error after 6th step: <b>ImportError: cannot import name 'python_2_unicode_compatible' from 'django.utils.encoding'</b><br>
Then navigate go to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py<br>
<b>Make the following changes in multiform.py:</b><br>
(i) Change <b>from django.utils.encoding import python_2_unicode_compatible</b> to <b>from six import python_2_unicode_compatible</b><br>
(ii) Change <b>from django.utils.six.moves import reduce</b> to <b>from six.moves import reduce</b><br><br>
<b>7. Create Super User:</b> python manage.py createsuperuser (To make yourself django admin)<br>
<b>8. Finally Run The Project:</b> python manage.py runserver (To run the project on server)

# How To Setup On Linux
<b>1. Clone This Project:</b> git clone https://github.com/SouravSehgal-3009/Eventima.git<br>
<b>2. Go to Project Directory:</b>  cd Eventima<br>
<b>3. Create a Virtual Environment:</b>  python3 -m venv eventima_env<br>
<b>4. Activate Virtual Environment:</b> source enventima_env/bin/activate<br>
<b>5. Install Requirements Package:</b> pip install -r requirements.txt<br>
<b>6. Migrate Database:</b> python manage.py migrate<br><br>
If you get an error after 6th step: <b>ImportError: cannot import name 'python_2_unicode_compatible' from 'django.utils.encoding'</b><br>
Then navigate go to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py<br>
<b>Make the following changes in multiform.py:</b><br>
(i) Change <b>from django.utils.encoding import python_2_unicode_compatible</b> to <b>from six import python_2_unicode_compatible</b><br>
(ii) Change <b>from django.utils.six.moves import reduce</b> to <b>from six.moves import reduce</b><br><br>
<b>7. Create Super User:</b> python manage.py createsuperuser (To make yourself django admin)<br>
<b>8. Finally Run The Project:</b> python manage.py runserver (To run the project on server)

# Preview
