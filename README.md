# Django Social Network

A social media web-application with Django.

## Features :

<li>Sign Up, Login, Logout</li>
<li>Public Profile view</li>
<li>Create, Edit, Delete Posts with customized text, pictures and links</li>
<li>Like, Comment / Reply, Save and Search posts</li>
<li>Follow and Unfollow users to view their posts</li>
<li>Friend Request</li>
<li>Notifications</li>
<li>Chats using websockets</li>
<li>Video Calls</li>

## Adding env variables

- Add env variables to ".test.env" and rename it to ".env"

## Installation

```bash
    $ python -m venv venv
    $ source venv/Scripts/activate
    (venv) pip install -r requirements.txt
    (venv) cd Django_Social_Network_App
    (venv) python manage.py makemigrations
    (venv) python manage.py migrate
    (venv) python manage.py createsuperuser
    (venv) python manage.py runserver
```

## Add django-allauth config

https://docs.allauth.org/en/latest/account/configuration.html

## Running Tests

To run tests, run the following command

```bash
  python manage.py test
```
