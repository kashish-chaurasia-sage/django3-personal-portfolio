Personal Portfolio - Django 3.0
==========================================================
My personal website. A simple, easily modifiable, based on Djnago that is deployed cuurently on pythonanywhere. Built using Django,bootsrap 4, python,sql,javascript, html/css, SCSS, github actions, and many other useful technologies.

* Website: [kashish.portfolio](https://kashishchaurasia.pythonanywhere.com/)

Features
--------
* Can easily showcase your projects by directly adding specific data to your database.
* Link your updated resume.
* Directly add your favourite bolgs and your intresting journals.
* Simple and straight forward digital portfolio to show up you skills along projects with links.

What you will learn while building up this project
--------------------------------------------------
You will learn how to:

* Add apps to your project
* Work with models and databases (including SQLite)
* Access the admin panel
* Create super users
* Make a responsive website with Bootstrap 4
* Work with static and media files
* Extending Templates
* Formating dates and purals

Getting Started
---------------
Install dependencies:

### Requirments
* Django==3.1.7
* Pillow==8.3.1
* requests==2.25.1
* python==2+

Clone the repository:

```bash
git clone https://gitlab.com/kashish10/django3-personal-portfolio.git
```

Go inside the folder :

```bash
cd personal_portfolio-project
```

Create super-user for your DB admin :

```bash
python manage.py createsuperuser
```

Make DB migrations :

```bash
python manage.py makemigrations

python manage.py migrate
```

Run server :

```bash
python manage.py runserver
```

Go-to Localhost :

Website: [localhost](http://127.0.0.1:8000/)

You can see that the resume is up, you can now modify the contents accordingly. All the static file, images or resume are in medial folder.

Contributing
------------
Contributions are actively encouraged. Please review the code. If you find a bug, or any improvement please [email me](kashish.chaurasia10@gmail.com), submit a pull request or submit an issue.


