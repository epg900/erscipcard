Erscipcard
=========
Erscipcard is a Django app to create personeli card. 
For each user,create a card and export it as pdf and docx documents.

Quick start
-----------
1.Add "erscipcard" to your INSTALLED_APPS setting like this:
```
INSTALLED_APPS = [
...,
'rest_framework',
'erscipcard',
]
```

2.Include the erscipcard URLconf in your project urls.py like this:

```
path('erscipcard/', include('erscipcard.urls')),
```

3.Run ``python manage.py makemigrations`` and ``python manage.py migrate``  to create the erscipcard models.

then run ``python manage.py createsuperuser`` to create personel for login erscipcard page.

4.Visit http://127.0.0.1:8000/erscipcard/ to create users and its cards.

first download card template , edit it and uplaod your custom template , then print cards.
