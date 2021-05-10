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
Then navigate to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py<br>
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
Then navigate to \Eventima\eventima_env\Lib\site-packages\betterforms\multiform.py<br>
<b>Make the following changes in multiform.py:</b><br>
(i) Change <b>from django.utils.encoding import python_2_unicode_compatible</b> to <b>from six import python_2_unicode_compatible</b><br>
(ii) Change <b>from django.utils.six.moves import reduce</b> to <b>from six.moves import reduce</b><br><br>
<b>7. Create Super User:</b> python manage.py createsuperuser (To make yourself django admin)<br>
<b>8. Finally Run The Project:</b> python manage.py runserver (To run the project on server)

# Admin Privileges
● Create/Update/Delete Categories: It enables you to create categories of events. Every
event created in future will belong to one of the categories. Admin can update info about
any category later also and even delete it.

● Create/Update/Delete Event: It enables you to add or create an event (can be multiple
events at a time) belonging to categories defined. Admin can update and delete the events
also. Event will have all the prerequisite details.

● Add Event Member: Admin can add members to the events, assign event to team
members and keep track of their activity.

Monitoring of online events will become easier with the help of EvenTima.

# Preview
![Admin Login](https://user-images.githubusercontent.com/60173032/117563577-89fbef00-b0c4-11eb-8cb2-e79e2b1a80a8.jpg)
![Dashboard](https://user-images.githubusercontent.com/60173032/117563582-8ec0a300-b0c4-11eb-9ea5-5bdc2665905c.jpg)
![Event Category List](https://user-images.githubusercontent.com/60173032/117563590-95e7b100-b0c4-11eb-931d-0c578ed6f5fc.jpg)
![Event List](https://user-images.githubusercontent.com/60173032/117563596-9a13ce80-b0c4-11eb-9fe5-2fced77f11bb.jpg)
![Event User Wish List](https://user-images.githubusercontent.com/60173032/117563613-ad269e80-b0c4-11eb-9619-0cbc7aa551c3.jpg)
![User Points List](https://user-images.githubusercontent.com/60173032/117563617-b31c7f80-b0c4-11eb-9252-5353473bb8ae.jpg)

# You can see project description here
https://youtu.be/M0lEssCkukk

# References
https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p

https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa2FlcTBlakZHRzZaUTV4TUJXalZER3psbTd0QXxBQ3Jtc0tsNWM1QmZaY2ZrOURXbnctRnlvd3RJS2pObHVZVG5VOUJKNGU4eDVLcHpmalJSaHRNSW5WXzV4QUFCMF93QlJidXRBX3FiR3F4VmZwVWlpMkYtLVY1MUtGZUJEVjlZM1JxMTNsUVE0VlFaZGRWTUpUaw&q=https%3A%2F%2Fgithub.com%2FCoreyMSchafer%2Fcode_snippets%2Ftree%2Fmaster%2FDjango_Blog

https://github.com/iyanuashiri/meethub

https://github.com/msaad1999/KLiK-SocialMediaWebsite
