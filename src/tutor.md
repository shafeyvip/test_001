**********
https://djangopackages.org/
https://djangopackages.org/packages/p/django-slick-reporting/
django-slick-reporting
https://django-slick-reporting.com/product-sales/

**********
virtualenv -p python test_001
cd test_001
mkdir src
.\Scripts\activate
cd .\src\

pip install django
pip install django-bootstrap5
django-admin startproject project .
python manage.py startproject .project
python manage.py startapp device
python manage.py startapp home
python manage.py startapp employee

python manage.py startapp accounts

python manage.py startapp contact
python manage.py startapp product
python manage.py startapp ticket

python manage.py startapp inventory
python manage.py startapp users
python manage.py startapp store


pip freeze > requirements.txt
pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate
**python manage.py createsuperuser**

python manage.py collectstatic

python manage.py runserver 192.168.0.206:8976


git add .
git commit -m "add basic 4 apps in our project"
git push
*******
- frontend template
- virtualenv:
  - creat
  - activate [widows : source ./scripts/activate]
  - pip install
  - deactivate

- upload progect on github

- url : path
- view : logic
- models : db
- templates : frontend




Relations :
    - One-to-Many  [Auther - Posts]          Foreginkey
    - Many-to-Many [Admin_User - Groups]       
    - One-to-One   [User - Profile]

-----------------
** django model queryset
** django template language
** django pagination
** django slug

-----------------

static files : [frontend] images, css, javascript

media files : [upload] images

---------------

- dashboard 
    - count date (tickets, device, employees)
- Export (PDF)
    pip install reportlab
- Export (Excel)  (Done)
    pip install django-import-export
    'import_export', #on settings 
    
- Import (Excel)  (Done)

- Print

-----------------

- Login (Done)
- Logout (Done)
- Profiles (Done)
- Permissions (Done)
- Search (Done)

-----------------
- Calendar
-----------------
- Reports
-----------------
- the code auto created
-----------------

{% static '

' %}

-----------------

