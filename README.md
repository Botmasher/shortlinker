# Shortlinker

This project is a bookmark server or URL-shortening service with no persistent storage.
Building began from an exercise for the Udacity [HTTP web servers](https://classroom.udacity.com/courses/ud303) class.

This server accepts a URL and a short name, checks that the URL actually works (returns HTTP 200), then stores it in a Python dictionary.

See the app [running on Heroku](shortlinker.herokuapp.com).

Open `ShortlinkerServer.py` for the main code.
