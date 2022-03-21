# install django project
  django-admin startproject project name
#install django app
  python manage.py startapp appname
#install virtual env
  pip install virtualenvwrapper-win
  #create a name in virtual env
    mkvirtualenv name
  #to open virtual env
   workon virtualenvname
# add databse to django project
  >first add data base  to django project
  >start zamp
  >install my sql connectivity
    *pip install mysqlclient
    * python manage.py makemigrations
    * python manage.py migrate
