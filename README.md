Usage
------

Let's pretend you want to create a Django project called "djangoreact". Rather than using ``startproject``
and then editing the results to include your name, email, and various configuration issues that always get forgotten until the worst possible moment, get cookiecutter_ to do all the work.

First, get Cookiecutter. Trust me, it's awesome::

    $ pip install "cookiecutter>=1.4.0"

Now run it against this repo::

    $ cookiecutter https://github.com/prabhatpankaj/cookiecutter-django-react-on-zappa

You'll be prompted for some values. Provide them, then a Django project will be created for you.
