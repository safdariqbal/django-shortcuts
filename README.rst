Django shortcuts
================

You spend too much time typing ``python manage.py``.

Usage
-----

This fork of django-shortcuts installs a ``dj`` binary that proxies
Django's ``manage.py`` and ``django-admin.py`` scripts.

::

    $ dj <command or shortcut>

    $ cd any/project/subdirectory
    $ dj <command or shortcut>

Requirements
------------

Some commands require additional packages

+ South
+ Haystack
+ Django Command Extensions


Shortcuts
---------

::

    # Django
    'c'  : 'collectstatic',
    'r'  : 'runserver',
    'sd' : 'syncdb',
    'sp' : 'startproject',
    'sa' : 'startapp',
    't'  : 'test',
    
    # Shell
    'd'  : 'dbshell',
    's'  : 'shell',
    
    # Auth
    'csu': 'createsuperuser',
    'cpw': 'changepassword',
    
    # South
    'm'  : 'migrate',
    'sm' : 'schemamigration',
    
    # Haystack
    'ix' : 'update_index',
    'rix': 'rebuild_index',
    
    # Django Extensions
    'sk' : 'generate_secret_key',
    'rdb': 'reset_db',
    'rp' : 'runserver_plus',
    'shp': 'shell_plus',
    'url': 'show_urls',
    'gm' : 'graph_models',
    'rs' : 'runscript'

Installation
------------

::

    $ pip install git+https://github.com/safdariqbal/django-shortcuts
