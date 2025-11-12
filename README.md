env\Scripts\activate
cd online_therapist_booking
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

