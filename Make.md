conda -V
conda update conda
conda create -n Django

conda activate Django
conda install -n yourenvname [package]

(Django):   source deactivate

(Django):   conda update --all

(Django):   pip install Django
(Django):   python3 -m django --version


(Django):   django-admin startproject mysite
(Django):   python3 manage.py runserver

(Django):   python3 manage.py startapp polls

python3 manage.py makemigrations polls
python3 manage.py sqlmigrate polls 0001
python3 manage.py migrate



(Django):   pip install django_taggit
(Django):   conda install -c conda-forge psycopg2-binary
(Django):   pip install Markdown

(Django):   conda update --all
(Django):   pip freeze > requirements.txt

(Django):   cd /Users/MzB/Desktop/SOFTWARE/Django-3-by-Example-master/MyBlog
(Django):   django-admin startproject mysite

cp Chapter 2

settings.py:

EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'dirk.mzb@googlemail.com'
EMAIL_HOST_PASSWORD = 'SN00P999'
EMAIL_PORT = 587
EMAIL_USE_TLS = True

(Django):   # python manage.py makemigrations
(Django):   python manage.py migrate
(Django):   python manage.py createsuperuser VN+a=5(xtJ§8Qrd+
(Django):   python manage.py runserver

(Django):  django-admin startproject mysite


(Django):  pip install Markdown
(Django):  
(Django):  
(Django):  
(Django):  
(Django):  
(Django):  
(Django):  



conda env create -f xl310.yml
conda activate xl310
(xl310):  pip install Django
(xl310):  conda update --all
(xl310):  pip freeze > requirements.txt
django-admin startproject mysite

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

Anpassung settings.py

python manage.py shell
from django.core.mail import sent_mail


python manage.py startapp blog
pip install django_taggit
conda install -c conda-forge psycopg2-binary
pip install Markdown

from django.contrib.auth.models import User
from blog.models import Post
user = User.objects.get(username='mzb')
post = Post(title='Another post',
            slug='another-post',
            body='Post body.',
            author=user)
post.save()

Post.objects.create(title='One more post', 
                    slug='one-more-post',
                    body='Post body.',
                    author=user)

post.title ='New title'
post.save()

all_posts = Post.objects.all()
Post.objects.all()