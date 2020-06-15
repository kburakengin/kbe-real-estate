
# KBE-Real-estate-project

  This is a simple real estate project for myself to improve my skills with Django.The database i choose is PostgreSQL. Users can simply register, login and logout. They have their own dashboard and they can see their latest inquiry on their dashboard page. Users doesn`t have to be registered, they can inquiry without being logged in. They can search with keywords,city,state,etc. according to their likings and what they search for. When users made their inquiry it sends and email to the responsible realtor. To be able to do that you should use your own email and password to the areas which says 'Your email' or 'Your password'. Listings can only be created from admin panel which is also customized. The front-end was not made by me , but i understand the every detail of it.

  

## Install guide

##### Clone the repo

```bash
$ git clone https://github.com/Kburak/kbe-real-estate.git
$ cd kbe-real-estate
```

##### Create the virtualenv and activate it
```bash
$ python3 -m venv venv
$ . venv/bin/activate
```

##### Or on Windows cmd::
```bash
    $ py -3 -m venv venv
    $ venv\Scripts\activate.bat
```

##### Install dependencies
```bash
$ pip install -r requirements.txt
```

####Create a Super User to access admin panel
```bash
$ python manage.py createsuperuser
```

####Make Migrations
```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

####Run the app
```bash
$ python manage.py runserver
```
