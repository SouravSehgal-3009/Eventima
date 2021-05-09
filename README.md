# Eventima
EvenTima is an event management webapp. Due to COVID-19 our new normal life is shifted to the virtual world of the internet. In this scenario it is very difficult to organize and manage an event. There does not exist any well structured event management system for the schools and universities which can help in managing the events smoothly in which they can manage all the events, the team members of the event and people who are participating in that event. Thus, it is the need of the hour to propose an event management system that can fulfill these requirements. My project Eventima is a step in this way.

# How To Setup On Windows
Clone This Project- git clone https://github.com/SouravSehgal-3009/Eventima.git
Go to Project Directory cd Eventima
Create a Virtual Environment- python -m venv eventima_env
Activate Virtual Environment- eventima_env\Scripts\activate.bat
Install Requirements Package- pip install -r requirements.txt

Now go to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py
line 15 should be= from six import python_2_unicode_compatible
line 17 should be- from six.moves import reduce

Migrate Database- python manage.py migrate
Create Super User- python manage.py createsuperuser
Finally Run The Project- python manage.py runserver







# How To Setup On Linux
Clone This Project- git clone https://github.com/SouravSehgal-3009/Eventima.git
Go to Project Directory cd Eventima
Create a Virtual Environment- python3 -m venv env
Activate Virtual Environment- source env/bin/activate
Install Requirements Package- pip install -r requirements.txt
Migrate Database- python manage.py migrate
Create Super User- python manage.py createsuperuser
Finally Run The Project- python manage.py runserver
