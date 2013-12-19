

# Dj_Ci_Test Project #


## About ##

Describe your project here.


## Prerequisites ##

- Python >= 2.7


## Installation ##

To bootstrap the project:

    cd path/to/dj_ci_test
    install system-wide dependencies from requirements-system.txt
    $ python bootstrap.py
    $ . env/bin/activate
    $ cp dj_ci_test/settings/local.py.template dj_ci_test/settings/local.py
    adjust your local settings, such as database adapter in settings/local.py
    $ python manage.py syncdb
    $ python manage.py runserver
