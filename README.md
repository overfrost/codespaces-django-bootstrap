# GitHub Codespaces ♥️ Django

Changes from default GitHub template
-Update Django version to 5.0.1
-Update django_broswer_reload to 1.01
-Removed hello world temp directory, template is ready to run new project
-Added bootstrap suppport

To begin your project
```python
django-admin startproject <<myproj>>
```



Welcome to your shiny new Codespace running Django! We've got everything fired up and running for you to explore Django.

You've got a blank canvas to work on from a git perspective as well. There's a single initial commit with the what you're seeing right now - where you go from here is up to you!

Everything you do here is contained within this one codespace. There is no repository on GitHub yet. If and when you’re ready you can click "Publish Branch" and we’ll create your repository and push up your project. If you were just exploring then and have no further need for this code then you can simply delete your codespace and it's gone forever.
To collect static files:

```python
python manage.py collectstatic
```
To run this application:

```python
python manage.py runserver
```
