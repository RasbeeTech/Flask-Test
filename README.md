# Flask test

A simple Blog Web App

Python version: 3.8.7  
Flask version: 1.1.2
SQLite version: 3.19.3

## Purpose:
Practice using Flask for future use.

## Details
The tutorial on [www.digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3) to create a web application.   

### Usage:
1. initiate database with the following command:  
```bash
python3 init_db.py
```
* which will create 'database.db' in the directory.  The database will contain 'posts' for the blog and will be initialized with 2 posts.  

2. In terminal, navigate to directory of app.py and enter:  
```bash
FLASK_APP=app.py flask run
```
3. In a web broswer, navigate to ```127.0.0.1:5000``` to access the web app.
