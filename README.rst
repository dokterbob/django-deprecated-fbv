django-deprecated-fbv
=====================

.. image:: https://badge.fury.io/py/django-deprecated-fbv.png
    :target: http://badge.fury.io/py/django-deprecated-fbv

.. image:: https://pypip.in/d/django-deprecated-fbv/badge.png
        :target: https://crate.io/packages/django-deprecated-fbv?version=latest

Deprecated Django function based generic views from Django 1.4 in a neat little package. Ugly little hack for deadlines and emergencies where Django 1.5 or 1.6 is necessary.

Usage
-----
1. Install the package from PIP::

       pip install django-deprecated-fbv

2. Change imports from ``django.views.generic`` into ``deprecated_fbv``.
3. Consider a more sensible strategy, like fixing your code to get rid of those pesky deprecation errors (yes, I left them in place).
