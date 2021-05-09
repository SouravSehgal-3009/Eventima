# Eventima
EvenTima is an event management webapp. Due to COVID-19 our new normal life is shifted to the virtual world of the internet. In this scenario it is very difficult to organize and manage an event. There does not exist any well structured event management system for the schools and universities which can help in managing the events smoothly in which they can manage all the events, the team members of the event and people who are participating in that event. Thus, it is the need of the hour to propose an event management system that can fulfill these requirements. Our project Eventima is a step in this way.

# How To Setup On Windows
Clone This Project- git clone https://github.com/SouravSehgal-3009/Eventima.git
Go to Project Directory:-  cd Eventima
Create a Virtual Environment:-  python -m venv eventima_env
Activate Virtual Environment:- eventima_env\Scripts\activate.bat
Install Requirements Package:- pip install -r requirements.txt

Now, on running the command:- python manage.py migrate, you will get error:-
                  ImportError: cannot import name 'python_2_unicode_compatible' from 'django.utils.encoding'

So, go to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py
Make the commands:-
from six import python_2_unicode_compatible
from six.moves import reduce

Migrate Database- python manage.py migrate
Create Super User- python manage.py createsuperuser (To make yourself admin)
Finally Run The Project- python manage.py runserver (To run the project on server)
