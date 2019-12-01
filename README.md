### Deploying a Flask Rest web service in AWS: An end-to-end tutorial

It's a simple Flask Rest web servcie that simulates a book store. It uses an intenal list in memory as database backend, but you can make a real DB by deploying the DB model to a relational database.

To tool around with the app directly, here's a quickstart guide. 

Clone this repo to your local machine. In the top level directory, create a virtual environment:
```
$ virtualenv flask-aws
$ source flask-aws/bin/activate
```
Now install the required modules:
```
$ pip install -r requirements.txt
```
To play with the app right away, you can use the in-memory list, now you can launch the app locally:
```
$ python application.py
```
And point your browser to http://0.0.0.0:80.
