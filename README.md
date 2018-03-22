# fwtheme-django-jasmin

Django app providing Django framework theme for Django-based web apps, themed for JASMIN. Requires lower-level fwtheme-django.

## Installation

`fwtheme-django-jasmin` can be installed directly from Github using pip for development, but for production the current version should be referenced on the ceda artefacts server.

```
$ pip install git+https://github.com/cedadev/fwtheme-django-jasmin.git
```

In `settings.py`, this app should have an entry in INSTALLED_APPS *before* fwtheme_django for correct precedence, as its templates should override those of `fwtheme-django`. orgtheme-jasmin and orgtheme are referenced directly in-place on the ceda artefacts server for production (but can be istalled and included in INSTALLED_APPS for development purposes only).

```
    'fwtheme_django_jasmin',
    'fwtheme_django',
```
